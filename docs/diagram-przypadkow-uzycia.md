# Diagram przypadków użycia

## System zarządzania drużyną piłkarską

```mermaid
flowchart LR

    U[Użytkownik]
    A[Administrator / Trener]

    subgraph SYSTEM[System zarządzania drużyną piłkarską]

        P1((Wyświetl zawodników))
        P2((Dodaj zawodnika))
        P3((Edytuj zawodnika))
        P4((Usuń zawodnika))
        P5((Wyświetl statystyki))
        P6((Wyświetl terminarz))
        P7((Zarządzaj meczami))
        P8((Wyświetl tabelę strzelców))

    end

    U --- P1
    U --- P5
    U --- P6
    U --- P8

    A --- P1
    A --- P2
    A --- P3
    A --- P4
    A --- P5
    A --- P6
    A --- P7
    A --- P8
```

## Opis

Użytkownik korzysta z systemu głównie w celu przeglądania
informacji o drużynie.

Administrator lub trener posiada dodatkowo możliwość modyfikowania
danych zawodników oraz meczów.
