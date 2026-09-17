# PU-01 – Wyszukaj książkę

## Nazwa

Wyszukaj książkę

## Aktor główny

Czytelnik

## Cel

Odnalezienie w katalogu książki spełniającej określone kryteria,
np. tytuł lub autor.

## Warunki wstępne

- Czytelnik ma dostęp do systemu.
- System jest dostępny poprzez stronę WWW, aplikację lub terminal
  w bibliotece.
- Zalogowanie nie jest wymagane.
- Wyszukiwanie jest dostępne publicznie.

## Warunki końcowe

System wyświetla listę książek pasujących do podanych kryteriów
wraz z informacją o dostępności egzemplarzy.

## Kryteria wyszukiwania

Czytelnik może wyszukiwać książki według:

- tytułu,
- autora.

## Przebieg podstawowy

1. Czytelnik otwiera formularz wyszukiwania.
2. Czytelnik wprowadza kryterium wyszukiwania.
3. System waliduje dane wejściowe.
4. System przeszukuje bazę danych katalogu.
5. System zwraca listę pasujących pozycji.
6. System wyświetla informacje:
   - tytuł,
   - autor,
   - liczba dostępnych egzemplarzy,
   - lokalizacja.
7. Czytelnik przegląda wyniki.

## Przypadki alternatywne

### A1 – Brak podanego kryterium

1. Czytelnik nie podaje żadnego kryterium.
2. System informuje, że należy podać kryterium wyszukiwania.
3. Czytelnik ponownie wprowadza dane.

### A2 – Brak wyników

1. System nie znajduje książek spełniających kryteria.
2. System wyświetla komunikat o braku wyników.
3. Czytelnik może zmienić kryteria wyszukiwania.

### A3 – Nieprawidłowe dane

1. System wykrywa nieprawidłowe dane wejściowe.
2. System wyświetla komunikat o błędzie.
3. Czytelnik poprawia dane.

## Rezultat

Czytelnik otrzymuje listę książek odpowiadających podanym kryteriom
wraz z informacją o liczbie dostępnych egzemplarzy i ich lokalizacji.
