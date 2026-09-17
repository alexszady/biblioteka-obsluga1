# PU-01 – Wyświetl zawodników

## Aktor główny

Użytkownik

## Cel

Wyświetlenie listy zawodników należących do drużyny wraz z
podstawowymi informacjami o każdym zawodniku.

## Warunki wstępne

- Użytkownik ma dostęp do systemu.
- System jest uruchomiony.
- Baza danych jest dostępna.

## Warunki końcowe

System wyświetla listę zawodników wraz z ich podstawowymi
informacjami i statystykami.

## Przebieg podstawowy

1. Użytkownik otwiera aplikację.
2. Użytkownik przechodzi do sekcji „Zawodnicy”.
3. System pobiera listę zawodników z bazy danych.
4. System przetwarza pobrane dane.
5. System wyświetla listę zawodników.
6. Użytkownik przegląda dane.

## Dane prezentowane użytkownikowi

Dla każdego zawodnika system wyświetla:

- imię i nazwisko,
- numer zawodnika,
- pozycję,
- liczbę rozegranych meczów,
- liczbę zdobytych goli,
- liczbę asyst.

## Przypadki alternatywne

### A1 – Brak zawodników

1. System pobiera dane z bazy.
2. System nie znajduje żadnego zawodnika.
3. System wyświetla komunikat informujący o braku zawodników.

### A2 – Błąd połączenia z bazą danych

1. System próbuje pobrać dane.
2. Występuje błąd bazy danych.
3. System wyświetla komunikat o błędzie.
4. Dane nie zostają wyświetlone.

## Rezultat

Użytkownik może przeglądać aktualną listę zawodników drużyny.
