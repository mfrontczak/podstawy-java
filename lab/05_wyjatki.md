# Wyjątki

## Teoria 📝
Rozdział 7 - Wyjątki, asercje i dzienniki

## Zadania ✏️
1 Napisz program, który pobierze od użytkownika godzinę i wypiszę ją na ekranie, a następnie sprawdzi czy wartość mieści się w przedziale (0, 24). Jeśli nie należy wyrzucić *IllegalArgumentException* wraz z dokładnym opisem, a w *finally* wypisać „Do zobaczenia jutro!”

2 Napisz własny wyjątek o nazwie *TooFarException*, zwracający wiadomość „Jesteś za daleko” za każdym razem jak użytkownik poda liczbę większą niż 100.

3 Napisz program, który pobiera od użytkownika liczbę i wyświetla jej pierwiastek. Do obliczenia pierwiastka można użyć *sqrt()*
* w przypadku otrzymania ujemnej liczby należy wyrzucić wyjątek *IllegalArgumentException*  
* w sytuacji kiedy podany ciąg znaków nie będzie liczbą *InputMismatchException* należy umożliwić użytkownikowi podawanie danych w pętli while aż do momentu wpisania prawidłowej
