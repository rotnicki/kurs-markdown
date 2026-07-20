---
layout: default
title: "11. Obrazy i tekst alternatywny — lekcja dodatkowa"
---

Ta lekcja jest dodatkowa. Na początku można ją pominąć.

## Budowa zapisu obrazu

Obraz w Markdown można zapisać tak:

```markdown
![Opis obrazu](https://example.com/zdjecie.jpg)
```

Zapis przypomina link, ale rozpoczyna się wykrzyknikiem.

## Co znajduje się w nawiasach kwadratowych

W nawiasach kwadratowych wpisujemy **tekst alternatywny**, czyli krótki opis treści lub funkcji obrazu.

Przykład:

```markdown
![Czworo zawodników klubu z medalami po zakończeniu turnieju](https://example.com/medalisci.jpg)
```

## Dobry tekst alternatywny

Dobry opis:

- przekazuje najważniejszą informację;
- jest zwięzły;
- nie zaczyna się niepotrzebnie od słów „zdjęcie przedstawia”;
- nie powtarza całego podpisu znajdującego się obok;
- uwzględnia cel użycia obrazu.

## Obraz dekoracyjny

Jeżeli obraz jest wyłącznie ozdobny, tekst alternatywny może być pusty:

```markdown
![](https://example.com/ozdoba.jpg)
```

Decyzję o uznaniu obrazu za dekoracyjny należy podejmować ostrożnie.

## Podpis pod obrazem

Podpis nie jest tym samym co tekst alternatywny. Podpis jest widoczny dla wszystkich czytelników i może zawierać dodatkowe informacje, np. nazwiska.

Prosty zapis:

```markdown
![Zawodnicy klubu z medalami](https://example.com/medalisci.jpg)

Od lewej: Anna Nowak, Jan Kowalski i Piotr Wiśniewski.
```

## Ćwiczenie

Przygotuj zapis obrazu przedstawiającego zawodniczkę odbierającą złoty medal. Użyj przykładowego adresu:

```text
https://example.com/zloty-medal.jpg
```

## Rozwiązanie

```markdown
![Zawodniczka klubu odbiera złoty medal na podium](https://example.com/zloty-medal.jpg)
```

## Nawigacja

- [Poprzednia lekcja: Grawis i kod](10-kod-i-grawis.html)
- [Wróć do spisu lekcji](index.html)
- [Następna lekcja: Kompletny dokument](12-kompletny-dokument.html)
