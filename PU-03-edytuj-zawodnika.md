# PU-03 – Edytuj zawodnika

## Aktor główny

Administrator / Trener

## Cel

Zmiana danych istniejącego zawodnika.

## Warunki wstępne

- Zawodnik istnieje w systemie.
- Administrator / Trener ma dostęp do systemu.
- Baza danych jest dostępna.

## Warunki końcowe

Dane zawodnika zostają zaktualizowane w bazie danych.

## Przebieg podstawowy

1. Administrator / Trener otwiera listę zawodników.
2. Wybiera zawodnika.
3. Wybiera opcję „Edytuj”.
4. System wyświetla aktualne dane zawodnika.
5. Administrator / Trener zmienia wybrane dane.
6. Administrator / Trener zatwierdza zmiany.
7. System waliduje dane.
8. System aktualizuje rekord zawodnika w bazie danych.
9. System wyświetla komunikat potwierdzający wykonanie operacji.

## Dane możliwe do zmiany

- imię i nazwisko,
- numer,
- pozycja,
- liczba goli,
- liczba asyst,
- liczba występów.

## Przypadki alternatywne

### A1 – Niepoprawne dane

1. System wykrywa niepoprawne dane.
2. System wyświetla komunikat o błędzie.
3. Administrator / Trener poprawia dane.
4. System ponownie sprawdza dane.

### A2 – Anulowanie edycji

1. Administrator / Trener rozpoczyna edycję.
2. Rezygnuje z wprowadzania zmian.
3. System nie aktualizuje danych.
4. Dane pozostają bez zmian.

### A3 – Zawodnik nie istnieje

1. Administrator / Trener wybiera zawodnika.
2. System nie znajduje wybranego zawodnika.
3. System wyświetla komunikat o błędzie.

## Rezultat

Dane zawodnika są zaktualizowane i dostępne dla użytkowników systemu.
