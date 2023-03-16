# Podstawy

## Teoria 📝
Rozdział 4 - Obiekty i klasy

## Zadania ✏️
1. Utwórz klasę *Human* reprezentującą człowieka. *Human* musi posiadać takie pola jak **age**, **name** i **height**. Klasa powinna zawierać jeden pusty konstruktor oraz drugi wymagający podania wszystkich pól. Należy zastosować zasady hermetyzacji.
2. Utwórz klasę *Person* wraz ze zmienną **age**, która będzie podawana inicjalnie jako argument w konstruktorze, a następnie: 
    * przygotuj getter *getAge()* który zwróci aktualny wiek,
    * zdefiniuj metodę *yearPases()* która przy każdym wywołaniu zwiększy wiek w zadanej instancji (w konkretnym obiekcie) o 1,
    * zdefiniuj metodę *amIOld()* która zwróci string o wartosci *Teenager* w przypadku kiedy wiek <= 19 lat oraz *Adult* w każdym innym  
    * wywołaj klasę Person dla wieku równego 18 lat, a następnie sekwencję metod *yearPases(), amIOld(), yearPases(), amIOld()*.
3. Utwórz klasę *StringUtils* wraz z metodą **Boolean isAnagram(String s1, String s2)** sprawdzającą czy łańcuch s1 jest anagramem s2.  
*Anagram jest to wyraz lub wyrażenie powstałe przez przestawienie liter innego wyrazu lub wyrażenia.*
4. Utwórz klasę Calculator, która nie posiada konstruktora, ani żadnych atrybutów. Jej działanie ma opierać się tylko na polach statycznych. Powinna zawierać:
* stałą PI i e  
* boolean isOdd(int number) - true jeśli atrybut jest nieparzysty,
* boolean isEven(int number) - true jeśli atrybut jest parzysty,  
* double pierwiastekZ(double number) - pierwiastek z atrybutu,  
* int wartoscBez(int number) - wartość bezwzględna z atrybutu,  
* long zaokraglij(double number) - wartość zaokrąglona do góry,  
* double pow(double number, double pow) - atrybut podniesiony do zadanej potęgi,  
* int number add(int numberOne, int numberTwo) - zwraca sumę liczb

*Do rozwiązania tego zadania może być przydatna dokumentacja klasy Math https://docs.oracle.com/javase/8/docs/api/java/lang/Math.html (abs, sqrt, pow…)*