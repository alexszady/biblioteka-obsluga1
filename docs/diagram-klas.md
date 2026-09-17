
# Diagram klas

```mermaid
classDiagram

    class Czytelnik {
        +int id
        +string imie
        +string nazwisko
        +string email
        +wyszukajKsiazke()
        +zarezerwujKsiazke()
        +wypozyczKsiazke()
        +zwrocKsiazke()
    }

    class Bibliotekarz {
        +int id
        +string imie
        +string nazwisko
        +string email
        +zarzadzajKatalogiem()
        +obsluzWypozyczenie()
        +obsluzZwrot()
        +generujRaport()
    }

    class Ksiazka {
        +int id
        +string tytul
        +string autor
        +string isbn
        +string lokalizacja
    }

    class Egzemplarz {
        +int id
        +string numer
        +string status
        +string lokalizacja
    }

    class Rezerwacja {
        +int id
        +date dataRezerwacji
        +string status
    }

    class Wypozyczenie {
        +int id
        +date dataWypozyczenia
        +date terminZwrotu
        +date dataZwrotu
        +string status
    }

    class Katalog {
        +wyszukajPoTytule()
        +wyszukajPoAutorze()
        +dodajKsiazke()
        +usunKsiazke()
        +edytujKsiazke()
    }

    class Raport {
        +int id
        +string typ
        +date dataGenerowania
        +generuj()
    }

    Czytelnik "1" --> "0..*" Rezerwacja : posiada
    Czytelnik "1" --> "0..*" Wypozyczenie : posiada

    Ksiazka "1" --> "1..*" Egzemplarz : posiada

    Rezerwacja "*" --> "1" Ksiazka : dotyczy
    Wypozyczenie "*" --> "1" Egzemplarz : dotyczy

    Katalog "1" --> "0..*" Ksiazka : zawiera

    Bibliotekarz --> Katalog : zarządza
    Bibliotekarz --> Raport : generuje
```

## Opis klas

### Czytelnik

Reprezentuje osobę korzystającą z biblioteki.

### Bibliotekarz

Reprezentuje pracownika biblioteki.

### Ksiazka

Przechowuje informacje o książce.

### Egzemplarz

Reprezentuje konkretny egzemplarz książki.

### Rezerwacja

Przechowuje informacje o rezerwacji książki.

### Wypozyczenie

Przechowuje informacje dotyczące wypożyczenia książki.

### Katalog

Przechowuje informacje o książkach i umożliwia zarządzanie nimi.

### Raport

Reprezentuje raport wygenerowany przez bibliotekarza.
