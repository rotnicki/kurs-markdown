---
layout: page
title: "4. Nagłówki i struktura dokumentu"
---

## Czego nauczysz się w tej lekcji

Po tej lekcji będziesz umieć:

- tworzyć nagłówki różnych poziomów;
- dzielić dokument na części;
- używać poziomów nagłówków w prawidłowej kolejności.

## Do czego służą nagłówki

Nagłówki porządkują dokument i nazywają jego części. Pomagają szybko zrozumieć strukturę tekstu.

Czytnik ekranu może także używać nagłówków do szybkiego poruszania się po przetworzonym dokumencie.

## Jak utworzyć nagłówek

Na początku wiersza wpisz znak krzyżyka, potem jedną spację, a następnie treść.

Nagłówek poziomu pierwszego:

```markdown
# Wyniki mistrzostw Polski
```

Nagłówek poziomu drugiego:

```markdown
## Reprezentanci klubu
```

Nagłówek poziomu trzeciego:

```markdown
### Wyniki kobiet
```

## Co oznacza liczba krzyżyków

- `#` — nagłówek poziomu pierwszego, stojący najwyżej w strukturze dokumentu;
- `##` — nagłówek poziomu drugiego;
- `###` — nagłówek poziomu trzeciego, znajdujący się wewnątrz części oznaczonej nagłówkiem poziomu drugiego.

W większości prostych dokumentów wystarczą trzy poziomy.

## Zachowaj prawidłową kolejność

Poprawny zapis:

```markdown
# Wyniki zawodów

## Kobiety

### Klasyfikacja końcowa

## Mężczyźni

### Klasyfikacja końcowa
```

Nie przeskakuj bez potrzeby z poziomu drugiego od razu do czwartego.

Niepoprawny zapis:

```markdown
# Wyniki zawodów

#### Kobiety
```

## Po krzyżykach wpisz spację

Poprawny zapis:

```markdown
## Wyniki
```

Niepoprawny zapis:

```markdown
##Wyniki
```

## Nagłówek nie jest pogrubionym akapitem

Nie zastępuj nagłówka samym pogrubieniem.

Zalecany zapis:

```markdown
## Wyniki kobiet
```

Niezalecany zapis:

```markdown
**Wyniki kobiet**
```

Nagłówek określa strukturę. Pogrubienie jest tylko wyróżnieniem fragmentu tekstu.

## Ćwiczenie

Przygotuj strukturę dokumentu zawierającego:

- nagłówek poziomu pierwszego „Zebranie zarządu”;
- nagłówek poziomu drugiego „Termin i miejsce”;
- nagłówek poziomu drugiego „Porządek obrad”;
- nagłówek poziomu trzeciego „Sprawy organizacyjne” wewnątrz części „Porządek obrad”.

## Rozwiązanie

```markdown
# Zebranie zarządu

## Termin i miejsce

## Porządek obrad

### Sprawy organizacyjne
```

## Nawigacja

- [Poprzednia lekcja: Akapity](03-akapity.html)
- [Wróć do spisu lekcji](index.html)
- [Następna lekcja: Listy punktowane](05-listy-punktowane.html)
