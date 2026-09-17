# PU-07 – Wyświetl tabelę strzelców

## Aktor główny

Użytkownik

## Cel

Wyświetlenie zawodników według liczby zdobytych goli.

## Warunki wstępne

- Użytkownik ma dostęp do systemu.
- System jest uruchomiony.
- Baza danych jest dostępna.
- W systemie znajdują się zawodnicy.

## Warunki końcowe

System wyświetla tabelę strzelców.

## Przebieg podstawowy

1. Użytkownik otwiera aplikację.
2. Użytkownik przechodzi do sekcji „Tabela strzelców”.
3. System pobiera dane zawodników z bazy danych.
4. System sortuje zawodników według liczby zdobytych goli.
5. System tworzy tabelę strzelców.
6. System wyświetla tabelę.
7. Użytkownik przegląda wyniki.

## Informacje wyświetlane

Tabela zawiera:

- miejsce zawodnika,
- imię i nazwisko,
- liczbę zdobytych goli.

## Przypadki alternatywne

### A1 – Brak zawodników

1. System pobiera dane.
2. System nie znajduje zawodników.
3. System wyświetla informację o braku danych.

### A2 – Błąd bazy danych

1. System próbuje pobrać dane.
2. Występuje błąd.
3. System wyświetla komunikat o błędzie.

## Rezultat

Użytkownik może przeglądać tabelę strzelców drużyny.
