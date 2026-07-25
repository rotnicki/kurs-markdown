---
layout: page
title: "6. Listy numerowane"
---

## Czego nauczysz się w tej lekcji

Po tej lekcji będziesz umieć:

- tworzyć listę kroków wykonywanych w określonej kolejności;
- tworzyć prostą listę numerowaną wewnątrz innej listy.

## Kiedy używać listy numerowanej

Lista numerowana jest odpowiednia, gdy opisujesz:

- instrukcję;
- kolejne etapy;
- kolejność działań;
- program wydarzenia;
- ranking, jeżeli numery mają znaczenie.

## Jak utworzyć listę

Wpisz numer, kropkę, jedną spację i treść.

```markdown
1. Otwórz Notatnik.
2. Wpisz tekst.
3. Zapisz plik.
```

## Numer musi mieć kropkę

Prawidłowo:

```markdown
1. Pierwszy krok
2. Drugi krok
```

Nieprawidłowo:

```markdown
1) Pierwszy krok
2) Drugi krok
```

Niektóre programy rozpoznają również nawias, ale w kursie używamy najbardziej uniwersalnego zapisu z kropką.

## Używaj rzeczywistych numerów

Markdown pozwala czasem wpisać przy każdym elemencie `1.`, a program sam nada numery. Dla początkującego autora bardziej czytelne jest jednak wpisywanie rzeczywistej kolejności:

```markdown
1. Rejestracja
2. Rozgrzewka
3. Rozpoczęcie zawodów
```

## Lista numerowana wewnątrz listy

Jeden krok może składać się z kilku mniejszych czynności. Można wtedy umieścić listę numerowaną wewnątrz jednego elementu innej listy.

Taki zapis nazywa się listą zagnieżdżoną.

Przykład:

```markdown
1. Przygotuj dokument.
    1. Napisz treść.
    2. Dodaj nagłówki.
2. Sprawdź dokument.
    1. Sprawdź listy.
    2. Sprawdź linki.
3. Prześlij dokument redaktorowi.
```

Elementy listy wewnętrznej rozpoczynają się od czterech spacji.

Przed każdym elementem listy wewnętrznej wpisz:

1. cztery spacje;
2. numer i kropkę;
3. jedną spację;
4. treść elementu.

Nie używaj klawisza Tab. W różnych programach może on działać inaczej. W tym kursie do tworzenia wcięcia używamy czterech zwykłych spacji.

Dla zachowania czytelności najlepiej używać najwyżej jednego poziomu zagnieżdżenia.

## Ćwiczenie

Zapisz jako listę numerowaną następującą procedurę:

- przygotowanie dokumentu;
- sprawdzenie treści;
- przesłanie dokumentu redaktorowi;
- zachowanie kopii.

## Rozwiązanie

```markdown
1. Przygotuj dokument.
2. Sprawdź treść.
3. Prześlij dokument redaktorowi.
4. Zachowaj kopię.
```

## Ćwiczenie dodatkowe

Przygotuj listę opisującą publikację dokumentu:

- przygotowanie dokumentu: napisanie treści i dodanie nagłówków;
- sprawdzenie dokumentu: sprawdzenie list i linków;
- przekazanie dokumentu redaktorowi.

## Rozwiązanie ćwiczenia dodatkowego

```markdown
1. Przygotuj dokument.
    1. Napisz treść.
    2. Dodaj nagłówki.
2. Sprawdź dokument.
    1. Sprawdź listy.
    2. Sprawdź linki.
3. Przekaż dokument redaktorowi.
```

## Nawigacja

- [Poprzednia lekcja: Listy punktowane](05-listy-punktowane.html)
- [Wróć do spisu lekcji](index.html)
- [Następna lekcja: Pogrubienie i kursywa](07-wyroznienia.html)
