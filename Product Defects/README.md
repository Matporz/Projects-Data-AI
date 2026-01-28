# Poisson Product Defects

Projekt analizujący liczbę wadliwych produktów w procesie produkcyjnym
z wykorzystaniem rozkładu Poissona o parametrze λ = 7.

## Opis
Liczba defektów w ciągu dnia modelowana jest rozkładem Poissona.
Projekt pokazuje zarówno teoretyczne własności rozkładu,
jak i ich praktyczne zastosowanie poprzez symulację danych.

## Zakres analizy
- obliczenie prawdopodobieństwa wystąpienia dokładnej liczby defektów (PMF)
- analiza dni z wyjątkowo małą (≤ 4) i dużą (> 9) liczbą usterek
- generowanie danych symulowanych dla 365 dni produkcji
- porównanie wartości oczekiwanej z wynikami symulacji
- analiza maksimum liczby defektów w pojedynczym dniu
- wyznaczenie percentyli rozkładu (m.in. 90. percentyl)

## Wnioski
Symulowane dane potwierdzają własności rozkładu Poissona:
średnia liczba defektów w danych jest zbliżona do wartości oczekiwanej λ,
a ekstremalne wartości występują z niskim prawdopodobieństwem.

## Technologie
- Python
- NumPy
- SciPy (`scipy.stats.poisson`)
- Jupyter Notebook

## Źródło
Projekt edukacyjny inspirowany zadaniem z platformy Codecademy.
