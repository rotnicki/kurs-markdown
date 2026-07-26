---
layout: page
title: "Ściągawka Markdown"
---

Ta ściągawka przypomina podstawowe sposoby zapisywania dokumentów w Markdown.

Ta sama treść jest dostępna również w [prostym pliku tekstowym do otwarcia lub zapisania na komputerze](pliki/sciagawka-markdown.txt).

## Akapity

Pomiędzy kolejnymi akapitami pozostaw jeden pusty wiersz.

Zapis:

```markdown
Pierwszy akapit.

Drugi akapit.
```

## Nagłówki

Na początku wiersza wpisz odpowiednią liczbę znaków krzyżyka, następnie jedną spację i treść nagłówka.

### Nagłówek poziomu pierwszego

Zapis:

```markdown
# Nagłówek poziomu pierwszego
```

W prostym samodzielnym dokumencie używaj jednego nagłówka poziomu pierwszego.

### Nagłówek poziomu drugiego

Zapis:

```markdown
## Nagłówek poziomu drugiego
```

### Nagłówek poziomu trzeciego

Zapis:

```markdown
### Nagłówek poziomu trzeciego
```

Nagłówki powinny tworzyć logiczną strukturę. Nie pomijaj poziomów tylko po to, aby zmienić wygląd tekstu.

## Listy

### Lista punktowana

Każdy element rozpocznij łącznikiem i jedną spacją. Każdy element umieść w osobnym wierszu.

Zapis:

```markdown
- pierwszy element
- drugi element
- trzeci element
```

### Zagnieżdżona lista punktowana

Elementy listy wewnętrznej rozpocznij od czterech zwykłych spacji.

Zapis:

```markdown
- Dokumenty:
    - legitymacja
    - zgoda opiekuna
- Wyposażenie:
    - strój sportowy
    - woda
```

### Lista numerowana

Wpisz numer, kropkę, jedną spację i treść elementu. Każdy element umieść w osobnym wierszu.

Zapis:

```markdown
1. pierwszy krok
2. drugi krok
3. trzeci krok
```

### Zagnieżdżona lista numerowana

Elementy listy wewnętrznej rozpocznij od czterech zwykłych spacji.

Zapis:

```markdown
1. Przygotuj dokument.
    1. Napisz treść.
    2. Dodaj nagłówki.
2. Sprawdź dokument.
```

## Wyróżnienia

### Pogrubienie

Umieść dwie gwiazdki przed tekstem i dwie gwiazdki po tekście. Nie dodawaj spacji pomiędzy gwiazdkami a wyróżnianym tekstem.

Zapis:

```markdown
**ważny tekst**
```

### Kursywa

Umieść jedną gwiazdkę przed tekstem i jedną gwiazdkę po tekście.

Zapis:

```markdown
*tytuł książki lub wyróżniony tekst*
```

## Linki

Tekst linku umieść w nawiasach kwadratowych. Bezpośrednio po nich wpisz adres w nawiasach okrągłych.

Zapis:

```markdown
[Opis linku](https://example.com)
```

Tekst linku powinien informować, dokąd prowadzi odnośnik. Unikaj określeń takich jak „kliknij tutaj”.

## Cytaty

Na początku każdego cytowanego akapitu wpisz znak większości i jedną spację.

Zapis:

```markdown
> Treść cytatu.
```

## Obrazy

Rozpocznij zapis wykrzyknikiem. Tekst alternatywny umieść w nawiasach kwadratowych, a adres lub ścieżkę do obrazu w nawiasach okrągłych.

Zapis:

```markdown
![Krótki tekst alternatywny](https://example.com/obraz.jpg)
```

Tekst alternatywny powinien krótko przekazywać istotną treść lub funkcję obrazu.

## Kontrola przed przekazaniem dokumentu

Sprawdź, czy:

- prosty samodzielny dokument ma jeden nagłówek poziomu pierwszego;
- nagłówki występują w logicznej kolejności;
- pomiędzy akapitami znajdują się puste wiersze;
- każdy element listy znajduje się w osobnym wierszu;
- elementy listy wewnętrznej rozpoczynają się od czterech spacji;
- linki mają zrozumiałe i opisowe nazwy;
- gwiazdki i nawiasy występują parami;
- w dokumencie nie pozostały przypadkowe znaki;
- dokument jest zrozumiały po odczytaniu od początku do końca.

## Nawigacja

- [Ostatnia lekcja: Sprawdzanie tekstu i najczęstsze błędy](13-sprawdzanie.html)
- [Wróć na stronę główną kursu](index.html)
- [Źródła merytoryczne](15-zrodla.html)
