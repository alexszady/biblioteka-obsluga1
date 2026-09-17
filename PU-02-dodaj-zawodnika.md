# PU-02 – Dodaj zawodnika

## Aktor główny

Administrator / Trener

## Cel

Dodanie nowego zawodnika do systemu drużyny.

## Warunki wstępne

- Administrator / Trener ma dostęp do systemu.
- System jest uruchomiony.
- Baza danych jest dostępna.

## Warunki końcowe

Nowy zawodnik zostaje zapisany w bazie danych i pojawia się
na liście zawodników.

## Przebieg podstawowy

1. Administrator / Trener otwiera sekcję „Zawodnicy”.
2. Wybiera opcję „Dodaj zawodnika”.
3. System wyświetla formularz.
4. Administrator / Trener wpisuje imię i nazwisko.
5. Administrator / Trener podaje numer zawodnika.
6. Administrator / Trener wybiera pozycję.
7. Administrator / Trener wprowadza statystyki.
8. Administrator / Trener zatwierdza formularz.
9. System waliduje wprowadzone dane.
10. System zapisuje zawodnika w bazie danych.
11. System wyświetla komunikat potwierdzający dodanie zawodnika.

## Dane wejściowe

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
4. System ponownie przeprowadza walidację.

### A2 – Numer zawodnika jest już zajęty

1. System sprawdza podany numer.
2. System wykrywa, że numer jest już przypisany.
3. System wyświetla odpowiedni komunikat.
4. Administrator / Trener podaje inny numer.

### A3 – Anulowanie operacji

1. Administrator / Trener otwiera formularz.
2. Wybiera opcję anulowania.
3. System zamyka formularz.
4. Zawodnik nie zostaje dodany.

## Rezultat

Nowy zawodnik zostaje zapisany w systemie.
