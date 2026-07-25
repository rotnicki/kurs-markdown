---
layout: page
title: "12. Sprawdzanie tekstu i najczęstsze błędy"
---

## Sprawdzenie dokumentu krok po kroku

Po zakończeniu pisania sprawdź:

1. Czy dokument ma jeden wyraźny tytuł?
2. Czy kolejne części mają opisowe nagłówki?
3. Czy poziomy nagłówków tworzą logiczną kolejność?
4. Czy pomiędzy akapitami znajduje się pusty wiersz?
5. Czy każdy element listy znajduje się w osobnym wierszu?
6. Czy linki mają zrozumiałe nazwy?
7. Czy cytaty są oznaczone znakiem `>`?
8. Czy gwiazdki i nawiasy występują parami?
9. Czy w tekście nie pozostały przypadkowe znaki?
10. Czy dokument jest zrozumiały po odczytaniu od początku do końca?

## Błąd: brak spacji po znaku

Nieprawidłowo:

```markdown
##Wyniki
-Adam Nowak
>To jest cytat.
```

Prawidłowo:

```markdown
## Wyniki

- Adam Nowak

> To jest cytat.
```

## Błąd: niezamknięte pogrubienie

Nieprawidłowo:

```markdown
**Termin zgłoszeń upływa w piątek.
```

Prawidłowo:

```markdown
**Termin zgłoszeń upływa w piątek.**
```

## Błąd: spacja w linku pomiędzy nawiasami

Nieprawidłowo:

```markdown
[Regulamin] (https://example.com/regulamin)
```

Prawidłowo:

```markdown
[Regulamin](https://example.com/regulamin)
```

## Błąd: nagłówki użyte wyłącznie dla wyglądu

Nie twórz nagłówka tylko dlatego, że chcesz uzyskać większy tekst. Nagłówek powinien nazywać dokument albo jego część.

## Błąd: pogrubienie zamiast nagłówka

Mniej poprawnie:

```markdown
**Wyniki**
```

Poprawnie:

```markdown
## Wyniki
```

## Błąd: lista wpisana w jednym wierszu

Nieprawidłowo:

```markdown
- Anna - Jan - Piotr
```

Prawidłowo:

```markdown
- Anna
- Jan
- Piotr
```

## Jak sprawdzać znaki czytnikiem ekranu

Gdy coś nie działa:

1. Ustaw kursor na początku podejrzanego wiersza.
2. Czytaj tekst znak po znaku.
3. Sprawdź liczbę krzyżyków lub gwiazdek.
4. Sprawdź, czy po znaku znajduje się spacja.
5. Sprawdź, czy nawias albo wyróżnienie zostały zamknięte.
6. Porównaj zapis z przykładem w kursie.

## Najważniejsza zasada

Błąd składni zwykle nie niszczy treści. Najczęściej powoduje tylko, że dany fragment nie zostanie rozpoznany jako nagłówek, lista albo wyróżnienie. Można spokojnie wrócić do tekstu i poprawić znaki.

## Nawigacja

- [Poprzednia lekcja: Kompletny dokument](12-kompletny-dokument.html)
- [Wróć do spisu lekcji](index.html)
- [Następna strona: Ściągawka](14-sciagawka.html)
