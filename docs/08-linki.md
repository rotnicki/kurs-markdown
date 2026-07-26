---
layout: page
title: "8. Odnośniki, czyli linki"
---

## Czego nauczysz się w tej lekcji

Po tej lekcji będziesz umieć:

- utworzyć link;
- umieścić tekst linku w nawiasach kwadratowych, a adres w nawiasach okrągłych;
- napisać zrozumiały tekst linku.

## Budowa linku

Link składa się z dwóch części:

1. tekstu widocznego dla czytelnika;
2. adresu, do którego prowadzi.

Zapis:

```markdown
[Regulamin zawodów](https://example.com/regulamin)
```

Tekst linku umieszczamy w nawiasach kwadratowych:

```text
[Regulamin zawodów]
```

Adres umieszczamy bezpośrednio po nim w nawiasach okrągłych:

```text
(https://example.com/regulamin)
```

Pomiędzy nawiasem kwadratowym zamykającym a nawiasem okrągłym otwierającym nie ma spacji.

## Używaj opisowego tekstu

Dobrze:

```markdown
Przeczytaj [regulamin zawodów](https://example.com/regulamin).
```

Mniej dobrze:

```markdown
Aby przeczytać regulamin, [kliknij tutaj](https://example.com/regulamin).
```

Tekst linku powinien mieć sens również wtedy, gdy czytnik ekranu odczyta go bez otaczającego zdania.

## Nie wklejaj długiego adresu jako treści

Długi adres może być trudny do odsłuchania i zapamiętania.

Mniej czytelnie:

```markdown
https://example.com/dokumenty/2026/07/regulamin-zawodow-final.pdf
```

Czytelniej:

```markdown
[Regulamin zawodów w pliku PDF](https://example.com/dokumenty/2026/07/regulamin-zawodow-final.pdf)
```

## Ćwiczenie

Utwórz link o tekście:

```text
Formularz zgłoszeniowy
```

Prowadzący do adresu:

```text
https://example.com/zgloszenia
```

## Rozwiązanie

```markdown
[Formularz zgłoszeniowy](https://example.com/zgloszenia)
```

## Nawigacja

- [Poprzednia lekcja: Pogrubienie i kursywa](07-wyroznienia.html)
- [Wróć do spisu lekcji](index.html)
- [Następna lekcja: Cytaty blokowe](09-cytaty.html)
