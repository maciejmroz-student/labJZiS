
# 🖥️ Dokumentacja laboratoriów – *Języki znaczników i skryptowe*

**Prowadzący:** dr inż. Arkadiusz Mirakowski  
**Semestr:** letni  
**Forma zajęć:** laboratoria 

---

## Spis treści

- [Laboratorium 1](#laboratorium-1)
- [Laboratorium 2](#laboratorium-2)
- [Laboratorium 3](#laboratorium-3)
- [Laboratorium 4](#laboratorium-4)
- [Laboratorium 5](#laboratorium-5)
- [Laboratorium 6](#laboratorium-6)
- [Laboratorium 7](#laboratorium-7)
- [Laboratorium 8](#laboratorium-8)
- [Laboratorium 9](#laboratorium-9)
- [Laboratorium 10](#laboratorium-10)
- [Laboratorium 11](#laboratorium-11)

---

## Laboratorium 1 – Wprowadzenie do HTML i CSS

### Tematy:
- Struktura dokumentu HTML5
- Łączenie zewnętrznych arkuszy stylów (CSS)
- Formatowanie podstawowych elementów HTML

### Ćwiczenia:
- Dołączenie `bcstyl.css` do `bc.html`
- Stylowanie:
  - Kolor tła (`body`)
  - Nagłówki (`h1`, `h2`, `h3`)
  - Formularz (`form`)
  - Listy uporządkowane i nieuporządkowane (`ul`, `ol`)
  - Własne obrazki jako punktor listy (`list-style-image`)

```css
body {
  background-color: #bfe7be;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

h1 {
  text-align: center;
  color: #333;
}
```

---

## Laboratorium 2 – Zaawansowane stylowanie CSS

### Nowe zagadnienia:
- Obramowania (`border`)
- Tekst (`font`, `text-transform`, `text-align`)
- Kolory i czcionki w nagłówkach i akapitach

### Zadania:
- Dodanie sekcji „Akcje bookcrossingu” z 6 linkami graficznymi
- Efekty `hover` na obrazkach z linkami
- Modyfikacja stylów nagłówków, formularzy i tabel

---

## Laboratorium 3 – Tworzenie layoutu w HTML5

### Cele:
- Zaprojektowanie struktury strony zgodnej ze standardem HTML5
- Stosowanie znaczników: `header`, `nav`, `main`, `section`, `footer`

### Wymagania:
- Layout o stałej szerokości (np. 960px)
- Wyśrodkowanie przy pomocy `margin: 0 auto;`
- Osadzenie grafiki w nagłówku

```html
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>Moja Strona</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="banner.jpg" alt="Baner">
  </header>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="podstrona1.html">O nas</a></li>
    </ul>
  </nav>
</body>
</html>
```

---

## Laboratorium 4 – Opływanie i pozycjonowanie

### Praktyka:
- Modyfikacja layoutu z lab. 3 z użyciem `float`, `position`
- Tworzenie układu jak na stronie [Morgan Stanley](https://www.morganstanley.com)

### Używane właściwości:
- `float: left/right`
- `position: relative/absolute`
- `clear: both`

---

## Laboratorium 5 – Projekt przykładowego layoutu strony

### Zadanie:
- Stworzenie layoutu zgodnie z rysunkiem projektowym (bloki A1–A4, B1–B2)

### Specyfikacja:
- Bloki o określonych wymiarach i kolorach (`lightblue`, `yellow`)
- Dodanie nagłówka (`<h1>`), daty (`<h3>`), oraz dwóch list (`ul`, `ol`)

```plaintext
/nazwisko/
├── zadanie1/
├── zadanie2/
└── zadanie3/
```

### Umiejętności:
- Praca z box-model CSS
- Precyzyjne pozycjonowanie elementów
- Utrwalanie koncepcji klas i identyfikatorów CSS

---

## Laboratorium 6 – Nawigacja i podstrony

### Tematy:
- Tworzenie menu z linkami do podstron
- Zastosowanie znaczników `<nav>` i `:hover`

### Ćwiczenia:
- Stworzenie plików `podstrona1.html`, `podstrona2.html`
- 3 wersje nawigacji:
  - `nav-02` – pozioma klasyczna
  - `nav-03` – graficzna
  - `nav-06` – pionowa lista z grafikami

---

## Laboratorium 7 – Formularz HTML

### Zadanie:
- Stworzenie podstrony `formularz.html`
- Formularz z polami tekstowymi, selectem, textarea, buttonem
- Zastosowanie `placeholder` oraz `label`

### Stylowanie:
- Własny CSS formularza (`form { ... }`)
- Dopasowanie stylu do wyglądu całej strony

---

## Laboratorium 8 – Walidacja formularza z JavaScript

### Cele:
- Walidacja formularzy z JS
- Obsługa zdarzeń `onclick`

### Zadania:
1. Sprawdzenie czy pola tekstowe są wypełnione
2. Wyświetlenie danych obok pól formularza
3. Obliczanie pierwiastków równania kwadratowego

---

## Laboratorium 9 – Formularze: hasła, ceny, dane adresowe

### Składniki formularzy:
- `login`, `hasło`, `powtórz hasło`
- `cena`, `ilość`, `zniżka` (z walidacją typu liczbowego)
- Adres (ulica, kod pocztowy, miasto)

### Walidacja:
- Porównywanie pól (`hasło === powtórzHasło`)
- Sprawdzenie poprawności liczby (`parseInt`, `isNaN`)
- Weryfikacja formatu daty i kodu pocztowego

---

## Laboratorium 10 – Obsługa zdarzeń (addEventListener)

### Tematy:
- Użycie `addEventListener()` dla przycisków, inputów

### Formularze:
1. Puste pole tekstowe – komunikat
2. Checkboxy – komunikaty zależne od liczby zaznaczeń
3. Select (kolory)
4. Radio (opcje wyboru)

---

## Laboratorium 11 – Finalny projekt strony z walidacją

### Struktura strony:
- `header` – 1000x80px
- `main` – 666x440px (zawiera formularz)
- `aside` – 334x440px
- `footer` – 1000x80px

### Formularz:
- Pola: imię, email, wiek (1–120), PESEL (11 cyfr)
- JavaScript:
  - Walidacja z komunikatami obok pól
  - Alert z podsumowaniem jeśli wszystko OK

### Struktura katalogu:
```
/css/style.css
/js/script.js
index.html
```

---

## 📌 Uwagi końcowe:
- Po każdych zajęciach: archiwizacja projektu (`.zip`) i przesłanie przez **ILIAS**
- W projektach zachowana struktura katalogów: `z1`, `z2`, `z3`, `z4`, itd.
