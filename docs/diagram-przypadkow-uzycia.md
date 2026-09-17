
# Diagram przypadków użycia

## System obsługi biblioteki

```mermaid
flowchart LR

    C[Czytelnik]
    B[Bibliotekarz]

    subgraph SYSTEM[System obsługi biblioteki]

        W((Wyszukaj książkę))
        R((Zarezerwuj książkę))
        WY((Wypożycz książkę))
        Z((Zwróć książkę))
        K((Zarządzaj katalogiem))
        G((Generuj raporty))

    end

    C --- W
    C --- R
    C --- WY
    C --- Z

    B --- WY
    B --- Z
    B --- K
    B --- G
```

## Opis

### Czytelnik

Czytelnik może:

- wyszukać książkę,
- zarezerwować książkę,
- wypożyczyć książkę,
- zwrócić książkę.

### Bibliotekarz

Bibliotekarz może:

- obsługiwać wypożyczenia,
- obsługiwać zwroty,
- zarządzać katalogiem,
- generować raporty.
