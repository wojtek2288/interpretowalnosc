1-85 - cechy pierwotne
86-219 - wskaźniki finansowe
220 - flaga default, jeżeli 1 - firma zbankrutowała

tak naprawdę - 1-219 to zmienne, 220 - zmienna celu

Dwa modele:
- interpretowalny
- black-box

NaNy - braki danych

- lepiej na końcu robić model

- można korzystać z GPT <3, ważne żeby wnioski były dobre

## Przekształcenia
- mediana lub cutoffy na zbiorze treningowym to też na testowym

- interpretowalny - albo zmienne ciągłe albo zmienne dyskretne

## WSKAŹNIKI CIĄGŁE - tylko dla interpretowalnych, nie dla black-boxów
cut-offy - jak na lewo od wartości to przyjmujemy tą wartość (prawo - analog), jak model jest wrażliwy na outliery
y = log(x)
Gini dla wskaźnika przed i po przekształceniu

- zastosowanie cut-offów i stosujemy funkcje, np y=ln(x) lub y=exp(x)

## Kalibracja
- metoda Plata, metoda izotoniczna
- trzeba zrobić, żeby pd na próbce miało jakiś rozkład

## Grid search?