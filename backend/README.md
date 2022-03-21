# Python API - Interview Task
### Description
Z wykorzystaniem dowolnego frameworka dostępnego dla języka Python (np. Django lub Flask), stwórz aplikację do zarządzania zbiorem książek. Aplikacja ma realizować operacje CRUD na zestawie książek dostępnej z API Google - ​https://www.googleapis.com/books/v1/volumes?q=<book_title>​. Odpowiednie zaprojektowanie warstwy wizualnej (np. z wykorzystaniem Boostrapa) będzie atutem.  

### Tasks
1. Zamodeluj obiekty bazodanowe tak, by zawierały pola: ​tytuł, autor, data publikacji, numer ISBN, liczba stron, link do okładki i język publikacji​.  
2. Stwórz 2 widoki: 
   a. Widok listy wszystkich znajdujących się w bazie książek z możliwością wyszukiwania po tytule, autorze i języku oraz zakresie dat publikacji (od - do). Lista ma zawierać wszystkie informacje z modelu wyświetlone w czytelny                sposób (np. w tabelce). 
   b. Widok z formularzem pozwalającym na ręczne dodawanie/edycję książek wraz z wyświetlaniem błędów walidacji. 
3. Stwórz widok, który pozwoli na import książek według słów kluczowych z API: https://developers.google.com/books/docs/v1/using#WorkingVolumes​. Wpisy tych książek muszą znaleźć się w ​bazie danych, która została stworzona w pierwszej części tego zadania. 
4. Utwórz API, które będzie posiadało listę książek z wyszukiwaniem i filtrowaniem przy użyciu query strings, jak w punkcie 2.a. z części pierwszej. 
5. Postaw aplikację na publicznie dostępnym serwerze - Heroku/AWS jest jedną z opcji. 
6. Napisz testy jednostkowe oraz sprawdź kod pod względem standardów ​PEP8​. 

Podpowiedź:
Formatowanie kodu/statyczną analizę możesz przeprowadzić przy użyciu takich narzędzi jak prospector/black.
