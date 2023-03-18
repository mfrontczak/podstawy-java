# Podstawy

## Teoria 📝
Rozdział 4 - Obiekty i klasy

## Zadania ✏️
1. Utwórz klasę *Human* reprezentującą człowieka. *Human* musi posiadać takie pola instancji jak **age**, **name** i **height**. Klasa powinna zawierać jeden pusty konstruktor oraz drugi wymagający podania wszystkich pól. Należy zastosować zasady hermetyzacji. W pliku Main.java stwórz nową instancję klasy używając każdego konstruktora.
2. Utwórz klasę *Person* wraz ze zmienną **age** z prywatnym modyfikatorem dostępu, która będzie podawana inicjalnie jako argument w konstruktorze, a następnie: 
    * przygotuj getter *getAge()* który zwróci aktualny wiek,
    * zdefiniuj metodę *yearPases()* która przy każdym wywołaniu zwiększy wiek w zadanej instancji (w konkretnym obiekcie) o 1,
    * zdefiniuj metodę *amIOld()* która zwróci string o wartosci *Teenager* w przypadku kiedy wiek <= 19 lat oraz *Adult* w każdym innym  
    * w pliku Main.java wywołaj klasę Person dla wieku równego 18 lat, a następnie sekwencję metod *yearPases(), amIOld(), yearPases(), amIOld()*.
3. Utwórz klasę *StringUtils* wraz z metodą **Boolean isAnagram(String s1, String s2)** sprawdzającą czy łańcuch s1 jest anagramem s2.  W pliku Main.java utwórz jedną instancję obiektu StringUtils, a następnie wywołaj trzykrotnie metodę *isAnagram()* dla różnych stringów.  
*Anagram jest to wyraz lub wyrażenie powstałe przez przestawienie liter innego wyrazu lub wyrażenia.*
4. Utwórz klasę Kalkulator, która nie posiada konstruktora, ani żadnych atrybutów. Jej działanie ma opierać się tylko na polach i metodach statycznych. Powinna zawierać:
    * stałą PI i e  
    * static boolean czyParzysty(int liczba) - true jeśli atrybut jest parzysty,  
    * static double pierwiastekZ(double liczba) - pierwiastek z atrybutu,  
    * static int wartoscBez(int liczba) - wartość bezwzględna z atrybutu,  
    * static long zaokraglij(double liczba) - wartość zaokrąglona do góry,  
    * static double pow(double liczba, double potega) - atrybut podniesiony do zadanej potęgi,  
    * static int suma(int[] liczby) - zwraca sumę wszystkich liczb w tablicy
    
    W pliku Main.java należy poprzez statyczne odwołanie użyć czterech wybranych metod. *Do rozwiązania tego zadania może być przydatna dokumentacja klasy Math https://docs.oracle.com/javase/8/docs/api/java/lang/Math.html (abs, sqrt, pow…)*