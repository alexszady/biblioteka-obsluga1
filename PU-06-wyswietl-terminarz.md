# PU-06 – Wyświetl terminarz

## Aktor główny

Użytkownik

## Cel

Wyświetlenie zaplanowanych oraz rozegranych meczów drużyny.

## Warunki wstępne

- Użytkownik ma dostęp do systemu.
- System jest uruchomiony.
- Baza danych jest dostępna.

## Warunki końcowe

System wyświetla terminarz meczów.

## Przebieg podstawowy

1. Użytkownik otwiera aplikację.
2. Użytkownik przechodzi do sekcji „Terminarz”.
3. System pobiera mecze z bazy danych.
4. System sortuje mecze według daty.
5. System wyświetla terminarz.
6. Użytkownik przegląda informacje o spotkaniach.

## Informacje wyświetlane dla meczu

- przeciwnik,
- data,
- godzina,
- miejsce,
- wynik.

## Przypadki alternatywne

### A1 – Brak meczów

1. System sprawdza bazę danych.
2. System nie znajduje żadnego meczu.
3. System wyświetla informację o braku spotkań.

### A2 – Błąd bazy danych

1. System próbuje pobrać terminarz.
2. Występuje błąd.
3. System wyświetla komunikat o błędzie.

## Rezultat

Użytkownik otrzymuje aktualny terminarz drużyny.
