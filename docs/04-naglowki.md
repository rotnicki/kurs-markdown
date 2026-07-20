---
layout: default
title: "4. Nagłówki i porządek dokumentu"
---

## Czego nauczysz się w tej lekcji

Po tej lekcji będziesz umieć:

- utworzyć tytuł dokumentu;
- podzielić dokument na części;
- używać poziomów nagłówków w prawidłowej kolejności.

## Do czego służą nagłówki

Nagłówki nazywają dokument i jego części. Pomagają szybko zrozumieć strukturę tekstu.

Czytnik ekranu może także używać nagłówków do szybkiego poruszania się po przetworzonym dokumencie.

## Jak utworzyć nagłówek

Na początku wiersza wpisz znak krzyżyka, potem jedną spację, a następnie treść.

Tytuł dokumentu:

```markdown
# Wyniki mistrzostw Polski
```

Nagłówek głównej części:

```markdown
## Reprezentanci klubu
```

Nagłówek mniejszej części:

```markdown
### Wyniki kobiet
```

## Co oznacza liczba krzyżyków

- `#` — nagłówek poziomu pierwszego, zwykle tytuł dokumentu;
- `##` — nagłówek poziomu drugiego, główna część;
- `###` — nagłówek poziomu trzeciego, część znajdująca się wewnątrz poprzedniej części.

W większości prostych dokumentów wystarczą trzy poziomy.

## Zachowaj prawidłową kolejność

Prawidłowy przykład:

```markdown
# Wyniki zawodów

## Kobiety

### Klasyfikacja końcowa

## Mężczyźni

### Klasyfikacja końcowa
```

Nie przeskakuj bez potrzeby z poziomu drugiego od razu do czwartego.

Nieprawidłowo:

```markdown
# Wyniki zawodów

#### Kobiety
```

## Po krzyżykach wpisz spację

Prawidłowo:

```markdown
## Wyniki
```

Nieprawidłowo:

```markdown
##Wyniki
```

## Nagłówek nie jest pogrubionym akapitem

Nie zastępuj nagłówka samym pogrubieniem.

Mniej poprawnie:

```markdown
**Wyniki kobiet**
```

Poprawnie:

```markdown
## Wyniki kobiet
```

Nagłówek określa strukturę. Pogrubienie jest tylko wyróżnieniem fragmentu tekstu.

## Ćwiczenie

Przygotuj strukturę dokumentu zawierającego:

- tytuł „Zebranie zarządu”;
- część „Termin i miejsce”;
- część „Porządek obrad”;
- podczęść „Sprawy organizacyjne” wewnątrz porządku obrad.

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
