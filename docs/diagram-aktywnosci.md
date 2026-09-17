
# Diagram aktywności – Wyszukaj książkę

```mermaid
flowchart TD

    A([Start])
    B[Czytelnik otwiera formularz wyszukiwania]
    C[Czytelnik wprowadza kryterium wyszukiwania]
    D[System waliduje dane wejściowe]
    E{Czy dane są poprawne?}
    F[System wyświetla komunikat o błędzie]
    G[System przeszukuje bazę danych katalogu]
    H{Czy znaleziono książki?}
    I[System wyświetla komunikat o braku wyników]
    J[System wyświetla listę pasujących książek]
    K[Czytelnik przegląda wyniki]
    L([Koniec])

    A --> B
    B --> C
    C --> D
    D --> E

    E -- Nie --> F
    F --> C

    E -- Tak --> G
    G --> H

    H -- Nie --> I
    I --> L

    H -- Tak --> J
    J --> K
    K --> L
```

## Opis

Diagram przedstawia przebieg wyszukiwania książki.

Czytelnik otwiera formularz, wprowadza kryteria wyszukiwania,
a system sprawdza poprawność danych.

Następnie system przeszukuje bazę danych katalogu.

Jeżeli znaleziono książki, system wyświetla listę wyników.

Jeżeli nie znaleziono żadnej książki, system wyświetla informację
o braku wyników.
