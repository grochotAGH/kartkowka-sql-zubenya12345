# Kartkówka: Obsługa PhpMyAdmin
**Czas trwania:** 10 minut

## Cel zadania
Wykaż się umiejętnością zarządzania bazą danych MariaDB przy użyciu panelu PhpMyAdmin w Twoim kontenerze LXC.

## Środowisko
*   **Adres:** `http://149.156.194.192:31XX/phpmyadmin` (podstaw `XX` za swój numer).
*   **Logowanie:** Dane z Lab 3.

## Zadania do wykonania (10 pkt)

1.  **Tworzenie bazy danych (2 pkt):**
    *   Utwórz bazę o nazwie `magazyn_db` (kodowanie `utf8_polish_ci`).

2.  **Struktura tabeli (4 pkt):**
    *   W bazie utwórz tabelę `produkty` (4 kolumny):
        *   `id`: `INT`, zaznacz `A_I` (Auto Increment).
        *   `nazwa`: `VARCHAR(100)`.
        *   `cena`: `DECIMAL(10,2)`.
        *   `stan_magazynowy`: `INT`.

3.  **Dane (2 pkt):**
    *   Użyj zakładki **Wstawianie**, aby dodać 2 dowolne rekordy.

4.  **SQL (2 pkt):**
    *   W zakładce **SQL** napisz zapytanie wyświetlające produkty o cenie > 100 zł.
    *   Wklej to zapytanie do sekcji poniżej.

## Oddanie zadania
1.  Wyeksportuj bazę do pliku `magazyn_db.sql` i wgraj go do tego repozytorium.
2.  Wklej zapytanie SQL poniżej.

---
## Rozwiązanie SQL
<<Tutaj wklej rozwiązanie>>
SELECT * FROM `produkty` WHERE cena > 100;
