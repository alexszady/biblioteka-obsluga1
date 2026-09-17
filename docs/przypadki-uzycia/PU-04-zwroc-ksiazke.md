# PU-04 – Zwróć książkę

## Nazwa

Zwróć książkę

## Aktor główny

Czytelnik

## Aktor wspierający

Bibliotekarz

## Cel

Zarejestrowanie zwrotu wypożyczonej książki.

## Warunki wstępne

- Książka została wcześniej wypożyczona.
- W systemie istnieje informacja o wypożyczeniu.

## Warunki końcowe

Zwrot zostaje zapisany w systemie.

Książka ponownie staje się dostępna.

## Przebieg podstawowy

1. Czytelnik przekazuje książkę bibliotekarzowi.
2. Bibliotekarz wyszukuje wypożyczenie.
3. System wyświetla informacje o wypożyczeniu.
4. Bibliotekarz zatwierdza zwrot.
5. System zapisuje datę zwrotu.
6. System aktualizuje dostępność egzemplarza.
7. System potwierdza wykonanie operacji.

## Przypadek alternatywny

### A1 – Brak wypożyczenia

1. Bibliotekarz wyszukuje książkę.
2. System nie znajduje aktywnego wypożyczenia.
3. System wyświetla komunikat.

## Rezultat

Książka zostaje zwrócona i oznaczona jako dostępna.
