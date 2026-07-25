---
layout: page
title: "5. Listy punktowane"
---

## Czego nauczysz się w tej lekcji

Po tej lekcji będziesz umieć:

- tworzyć listę elementów, których kolejność nie jest najważniejsza;
- tworzyć prostą listę punktowaną wewnątrz innej listy.

## Kiedy używać listy punktowanej

Lista punktowana jest dobra, gdy wymieniasz:

- uczestników;
- potrzebne dokumenty;
- wyposażenie;
- dyscypliny;
- niezależne informacje.

## Jak utworzyć listę

Na początku każdego elementu wpisz łącznik, jedną spację i treść.

```markdown
- showdown
- pływanie
- strzelectwo
```

## Każdy element w osobnym wierszu

Prawidłowo:

```markdown
- Anna Nowak
- Jan Kowalski
- Piotr Wiśniewski
```

Nieprawidłowo:

```markdown
- Anna Nowak - Jan Kowalski - Piotr Wiśniewski
```

## Pozostaw pusty wiersz przed listą i po niej

Taki zapis jest najbardziej czytelny i przewidywalny:

```markdown
W zawodach wystartowali:

- Anna Nowak
- Jan Kowalski

Dziękujemy wszystkim zawodnikom.
```

## Nie wpisuj ręcznie znaków ozdobnych

Nie używaj przypadkowych symboli, takich jak:

```text
• ◆ → ★
```

Standardowy łącznik jest prostszy i działa w wielu programach.

## Lista wewnątrz listy

Czasami jeden element listy trzeba podzielić na mniejsze elementy. Powstaje wtedy lista wewnątrz listy. Taki zapis nazywa się listą zagnieżdżoną.

Przykład:

```markdown
- Dyscypliny indywidualne:
    - showdown
    - pływanie
- Dyscypliny zespołowe:
    - goalball
    - piłka nożna
```

Elementy listy wewnętrznej rozpoczynają się od czterech spacji, a następnie od łącznika i jednej spacji.

Przed każdym elementem listy wewnętrznej wpisz:

1. cztery spacje;
2. łącznik;
3. jedną spację;
4. treść elementu.

Nie używaj klawisza Tab. W różnych programach może on działać inaczej. W tym kursie do tworzenia wcięcia używamy czterech zwykłych spacji.

Dla zachowania czytelności najlepiej używać najwyżej jednego poziomu zagnieżdżenia.

## Ćwiczenie

Utwórz listę punktowaną zawierającą:

- legitymację;
- strój sportowy;
- wodę;
- zgodę opiekuna.

## Rozwiązanie

```markdown
- legitymacja
- strój sportowy
- woda
- zgoda opiekuna
```

## Ćwiczenie dodatkowe

Utwórz listę punktowaną zawierającą dwie grupy:

- dokumenty: legitymacja i zgoda opiekuna;
- wyposażenie: strój sportowy i woda.

## Rozwiązanie ćwiczenia dodatkowego

```markdown
- Dokumenty:
    - legitymacja
    - zgoda opiekuna
- Wyposażenie:
    - strój sportowy
    - woda
```

## Nawigacja

- [Poprzednia lekcja: Nagłówki](04-naglowki.html)
- [Wróć do spisu lekcji](index.html)
- [Następna lekcja: Listy numerowane](06-listy-numerowane.html)
