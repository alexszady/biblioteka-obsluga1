# PU-05 – Wyświetl statystyki

## Aktor główny

Użytkownik

## Cel

Wyświetlenie statystyk zawodników drużyny.

## Warunki wstępne

- Użytkownik ma dostęp do systemu.
- System jest uruchomiony.
- Baza danych jest dostępna.

## Warunki końcowe

System wyświetla aktualne statystyki zawodników.

## Przebieg podstawowy

1. Użytkownik otwiera aplikację.
2. Użytkownik przechodzi do sekcji „Statystyki”.
3. System pobiera dane zawodników.
4. System przetwarza dane statystyczne.
5. System wyświetla statystyki.
6. Użytkownik przegląda statystyki zawodników.

## Prezentowane dane

System wyświetla:

- imię i nazwisko zawodnika,
- liczbę rozegranych meczów,
- liczbę zdobytych goli,
- liczbę asyst.

## Przypadki alternatywne

### A1 – Brak danych

1. System pobiera dane.
2. System nie znajduje danych statystycznych.
3. System wyświetla informację o braku statystyk.

### A2 – Błąd bazy danych

1. System próbuje pobrać dane.
2. Występuje błąd połączenia.
3. System wyświetla komunikat o błędzie.

## Rezultat

Użytkownik może przeglądać statystyki zawodników.
