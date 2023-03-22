# Dziedziczenie

## Teoria 📝
Rozdział 5 - Dziedziczenie

## Zadania ✏️
1 Napisz program, który utworzy:  
* **colorsTab** używając implementacji tablicy *new String[]*
* **colorsList** używając implementacji listy *new ArrayList<>()*  

a następnie w zależności od możliwości struktury  
* doda do niej 5 dowolnych nazw kolorów,
* wypisze na ekranie zawartość listy po przecinku,
* wstawi dodatkowy kolor na pierwszym miejscu listy,
* usunie kolory na dwóch ostatnich indeksach,
* sprawdzi czy w liście istnieje kolor czarny (true / false)  


2 Utwórz abstrakcyjną klasę **Vehicle**  
* zawierającą zmienne opisujące nazwę oraz liczbę kół
* zawierający pole typu wyliczeniowego enum określającego trudność prowadzenia **EASY, MEDIUM, HARD**
* zawierającą metodę  **getPrice()** zwracającą cenę na podstawie wzoru ilość kół * 1000  

a następnie utwórz trzy klasy dziedziczące po niej dziedziczące **Car**, **Motorcycle** oraz **Tricycle**, które:  
* będą miały konstruktory pozwalające na inicjalizację wszystkich pól z nadklasy  
* przesłonią metodę **toString()** wypisując unikalny string opisujący dany pojazd
* będą przysłaniać metodę **equals()** w taki sposób, że porównywane będzie tylko pole **brand**

Następnie utwórz instancję każdego z nich i dodaj je do jednej listy. W pętli wypisz cenę każdego z nich.

3 Napisz program pozwalający na rekrutację nowych pracowników (dopisywanie ich do listy) oraz wyświetlanie danych obecnych (wypisywanie z listy)  
* klasą nadrzędną będzie **Employee**, a dziedziczyć po niej będzie **Doctor** i **Miner**
* należy zaproponować atrybuty opisujące każdego z nich oraz części wspólne
* użytkownik ma możliwość utworzenia nowego pracownika za pomocą inputu z klawiatury oraz wypisania wszystkich już istniejących w bazie