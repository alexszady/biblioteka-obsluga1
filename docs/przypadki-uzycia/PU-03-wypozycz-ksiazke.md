# PU-03 – Wypożycz książkę

## Nazwa

Wypożycz książkę

## Aktor główny

Czytelnik

## Aktor wspierający

Bibliotekarz

## Cel

Umożliwienie czytelnikowi wypożyczenia książki.

## Warunki wstępne

- Czytelnik posiada konto.
- Czytelnik może dokonać wypożyczenia.
- Książka znajduje się w katalogu.
- Dostępny jest egzemplarz książki.

## Warunki końcowe

Wypożyczenie zostaje zapisane w systemie.

Liczba dostępnych egzemplarzy zostaje zmniejszona.

## Przebieg podstawowy

1. Czytelnik wybiera książkę.
2. Bibliotekarz identyfikuje czytelnika.
3. System sprawdza dostępność książki.
4. System sprawdza możliwość wypożyczenia.
5. Bibliotekarz zatwierdza wypożyczenie.
6. System zapisuje wypożyczenie.
7. System aktualizuje dostępność egzemplarza.
8. System wyświetla potwierdzenie.

## Przypadki alternatywne

### A1 – Brak dostępnych egzemplarzy

1. System sprawdza dostępność książki.
2. System stwierdza brak dostępnych egzemplarzy.
3. System wyświetla komunikat.

### A2 – Czytelnik nie może wypożyczyć książki

1. System sprawdza możliwość wypożyczenia.
2. System stwierdza brak możliwości wypożyczenia.
3. System wyświetla komunikat.

## Rezultat

Książka zostaje wypożyczona czytelnikowi.
