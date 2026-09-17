
# Diagram sekwencji – Wyszukaj książkę

```mermaid
sequenceDiagram

    actor Czytelnik
    participant System as System biblioteki
    participant Baza as Baza danych katalogu

    Czytelnik->>System: Otwiera formularz wyszukiwania
    System-->>Czytelnik: Wyświetla formularz

    Czytelnik->>System: Wprowadza kryterium wyszukiwania
    System->>System: Waliduje dane wejściowe

    alt Dane niepoprawne
        System-->>Czytelnik: Wyświetla komunikat o błędzie
    else Dane poprawne
        System->>Baza: Wyszukuje książki
        Baza-->>System: Zwraca pasujące pozycje
        System-->>Czytelnik: Wyświetla wyniki
        Czytelnik->>System: Przegląda wyniki
    end
```

## Opis

Diagram przedstawia komunikację pomiędzy czytelnikiem, systemem
biblioteki oraz bazą danych katalogu.

Czytelnik przekazuje kryterium wyszukiwania do systemu.

System sprawdza poprawność danych i wysyła zapytanie do bazy danych.

Baza danych zwraca pasujące książki.

System wyświetla czytelnikowi:

- tytuł,
- autora,
- liczbę dostępnych egzemplarzy,
- lokalizację.
