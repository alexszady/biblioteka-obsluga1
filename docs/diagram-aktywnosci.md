# Diagram aktywności – zarządzanie zawodnikiem

```mermaid
flowchart TD

    A([Start])
    B[Administrator otwiera listę zawodników]
    C[Wybiera operację]
    D{Jaka operacja?}

    E[Wprowadza dane zawodnika]
    F[System sprawdza dane]
    G{Dane poprawne?}
    H[System zapisuje zawodnika]

    I[Wybiera zawodnika]
    J[Zmienia dane zawodnika]
    K[System aktualizuje dane]

    L[Wybiera zawodnika]
    M[Potwierdza usunięcie]
    N[System usuwa zawodnika]

    O[System wyświetla listę zawodników]
    P([Koniec])

    A --> B
    B --> C
    C --> D

    D -->|Dodaj| E
    E --> F
    F --> G
    G -->|Nie| E
    G -->|Tak| H
    H --> O

    D -->|Edytuj| I
    I --> J
    J --> K
    K --> O

    D -->|Usuń| L
    L --> M
    M --> N
    N --> O

    O --> P
```

## Opis

Diagram przedstawia proces zarządzania zawodnikiem.

Administrator może dodać, edytować lub usunąć zawodnika.

Podczas dodawania danych system sprawdza ich poprawność.
