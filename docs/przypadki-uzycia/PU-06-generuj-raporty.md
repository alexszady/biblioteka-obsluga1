# PU-06 – Generuj raporty

## Nazwa

Generuj raporty

## Aktor główny

Bibliotekarz

## Cel

Umożliwienie bibliotekarzowi generowania raportów dotyczących
funkcjonowania biblioteki.

## Warunki wstępne

- Bibliotekarz jest zalogowany.
- Bibliotekarz posiada uprawnienia do generowania raportów.
- System posiada dane potrzebne do wygenerowania raportu.

## Warunki końcowe

System generuje raport zgodny z wybranymi kryteriami.

## Rodzaje raportów

System może generować raporty dotyczące:

- wypożyczeń,
- zwrotów,
- dostępności książek,
- rezerwacji,
- książek znajdujących się w katalogu.

## Przebieg podstawowy

1. Bibliotekarz otwiera moduł raportów.
2. Bibliotekarz wybiera rodzaj raportu.
3. Bibliotekarz określa kryteria raportu.
4. System sprawdza poprawność danych.
5. System pobiera dane z bazy.
6. System generuje raport.
7. System wyświetla raport bibliotekarzowi.

## Przypadek alternatywny

### A1 – Brak danych

1. System wyszukuje dane spełniające kryteria.
2. System nie znajduje danych.
3. System informuje bibliotekarza o braku danych.

## Rezultat

Raport zostaje wygenerowany i wyświetlony bibliotekarzowi.
