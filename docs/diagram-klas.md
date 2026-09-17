# Diagram klas

```mermaid
classDiagram

    class Zawodnik {
        +int id
        +string name
        +int number
        +string position
        +int goals
        +int assists
        +int appearances
    }

    class Mecz {
        +int id
        +string opponent
        +string match_date
        +string match_time
        +string location
        +string result
    }

    class SystemDruzyny {
        +wyswietlZawodnikow()
        +dodajZawodnika()
        +edytujZawodnika()
        +usunZawodnika()
        +wyswietlStatystyki()
        +wyswietlTerminarz()
        +wyswietlTabeleStrzelcow()
        +dodajMecz()
        +edytujMecz()
        +usunMecz()
    }

    class BazaDanych {
        +players
        +matches
        +pobierzZawodnikow()
        +dodajZawodnika()
        +edytujZawodnika()
        +usunZawodnika()
        +pobierzMecze()
        +dodajMecz()
        +edytujMecz()
        +usunMecz()
    }

    SystemDruzyny --> BazaDanych : korzysta
    BazaDanych --> Zawodnik : przechowuje
    BazaDanych --> Mecz : przechowuje
```

## Klasa Zawodnik

Przechowuje informacje o zawodniku:

- identyfikator,
- imię i nazwisko,
- numer,
- pozycję,
- gole,
- asysty,
- występy.

## Klasa Mecz

Przechowuje informacje o meczu:

- przeciwnika,
- datę,
- godzinę,
- miejsce,
- wynik.

## Baza danych

Baza danych przechowuje informacje o zawodnikach i meczach.

## System drużyny

System odpowiada za wykonywanie operacji na danych.
