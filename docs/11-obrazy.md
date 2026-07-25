---
layout: page
title: "10. Obrazy i tekst alternatywny — lekcja dodatkowa"
---

Ta lekcja jest dodatkowa. Na początku można ją pominąć.

## Osadzanie obrazu w dokumencie

Markdown nie tworzy obrazu ani nie zapisuje go wewnątrz dokumentu. Zapis w Markdown wskazuje osobny plik graficzny, który program wyświetlający dokument może osadzić w odpowiednim miejscu.

Obraz można osadzić za pomocą takiego zapisu:

```markdown
![Opis obrazu](https://example.com/zdjecie.jpg)
```

Zapis przypomina link, ale rozpoczyna się wykrzyknikiem.

Składa się z trzech części:

1. wykrzyknika, który oznacza odwołanie do obrazu;
2. tekstu alternatywnego umieszczonego w nawiasach kwadratowych;
3. adresu lub ścieżki do pliku obrazu umieszczonych w nawiasach okrągłych.

## Co znajduje się w nawiasach kwadratowych

W nawiasach kwadratowych wpisujemy **tekst alternatywny**, czyli krótki opis treści lub funkcji obrazu.

Przykład:

```markdown
![Czworo zawodników klubu z medalami po zakończeniu turnieju](https://example.com/medalisci.jpg)
```

## Co znajduje się w nawiasach okrągłych

W nawiasach okrągłych wpisujemy adres lub ścieżkę prowadzącą do pliku obrazu.

Może to być adres internetowy:

```markdown
![Zawodnicy z medalami](https://example.com/medalisci.jpg)
```

Może to być również ścieżka do pliku znajdującego się w tym samym projekcie:

```markdown
![Zawodnicy z medalami](obrazy/medalisci.jpg)
```

Sam plik Markdown nie zawiera obrazu. Zawiera jedynie informację, gdzie znajduje się plik graficzny, który ma zostać wyświetlony.

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

Przygotuj zapis osadzający obraz przedstawiający zawodniczkę odbierającą złoty medal. Użyj przykładowego adresu:

```text
https://example.com/zloty-medal.jpg
```

## Rozwiązanie

```markdown
![Zawodniczka klubu odbiera złoty medal na podium](https://example.com/zloty-medal.jpg)
```

## Nawigacja

- [Poprzednia lekcja: Cytaty blokowe](09-cytaty.html)
- [Wróć do spisu lekcji](index.html)
- [Następna lekcja: Kompletny dokument](12-kompletny-dokument.html)
