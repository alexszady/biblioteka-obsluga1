# PU-04 – Usuń zawodnika

## Aktor główny

Administrator / Trener

## Cel

Usunięcie zawodnika z systemu drużyny.

## Warunki wstępne

- Zawodnik istnieje w systemie.
- Administrator / Trener ma dostęp do systemu.
- Baza danych jest dostępna.

## Warunki końcowe

Zawodnik zostaje usunięty z bazy danych.

## Przebieg podstawowy

1. Administrator / Trener otwiera listę zawodników.
2. Wybiera zawodnika.
3. Wybiera opcję „Usuń”.
4. System wyświetla komunikat z prośbą o potwierdzenie.
5. Administrator / Trener potwierdza usunięcie.
6. System usuwa zawodnika z bazy danych.
7. System odświeża listę zawodników.
8. System wyświetla komunikat potwierdzający usunięcie.

## Przypadki alternatywne

### A1 – Anulowanie usunięcia

1. System wyświetla prośbę o potwierdzenie.
2. Administrator / Trener wybiera „Anuluj”.
3. System nie usuwa zawodnika.
4. Zawodnik pozostaje na liście.

### A2 – Zawodnik nie istnieje

1. Administrator / Trener wybiera zawodnika.
2. System nie znajduje wskazanego rekordu.
3. System wyświetla komunikat o błędzie.

## Rezultat

Zawodnik zostaje usunięty z systemu.
