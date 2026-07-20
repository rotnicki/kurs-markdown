---
layout: default
title: "10. Grawis i pokazywanie kodu"
---

Ta lekcja jest przydatna głównie wtedy, gdy chcesz pokazać komuś dokładną składnię Markdown. W typowym komunikacie klubowym rzadko będzie potrzebna.

## Co to jest grawis

Grawis, nazywany również po angielsku *backtick*, wygląda tak:

```text
`
```

Nie jest tym samym znakiem co apostrof:

```text
'  apostrof
`  grawis
```

## Krótki fragment składni w zdaniu

Aby pokazać jeden znak albo krótki zapis bez jego przetwarzania, otocz go pojedynczymi grawisami.

W pliku wpisujesz:

```markdown
Nagłówek poziomu drugiego rozpoczyna się od `##`.
```

Czytelnik zobaczy znak `##` jako przykład, a nie nagłówek.

## Większy przykład

Większy fragment umieszczamy pomiędzy wierszami zawierającymi po trzy grawisy.

W pliku kursu zapis może wyglądać tak:

````markdown
```markdown
## Wyniki

- Anna Nowak
- Jan Kowalski
```
````

Słowo `markdown` po otwierających trzech grawisach informuje program, jaki język pokazujemy. GitHub może dzięki temu pokolorować składnię. Nie zmienia ono treści przykładu.

## Dlaczego nie ma pustego wiersza po słowie `markdown`

Pierwszy wiersz:

````text
```markdown
````

otwiera blok i podaje nazwę języka. Następny wiersz jest już pierwszym wierszem przykładu.

Pusty wiersz można wstawić, ale wtedy stanie się częścią pokazywanego przykładu.

## Jak pokazać trzy grawisy

Gdy przykład sam zawiera trzy grawisy, zewnętrzny blok można otworzyć i zamknąć czterema grawisami. Właśnie tak zbudowano przykład powyżej.

## Ćwiczenie

Zapisz zdanie, w którym pokazujesz dokładny zapis pogrubienia:

```text
**ważny tekst**
```

## Rozwiązanie

```markdown
Aby pogrubić fragment, wpisz `**ważny tekst**`.
```

## Nawigacja

- [Poprzednia lekcja: Cytaty blokowe](09-cytaty.html)
- [Wróć do spisu lekcji](index.html)
- [Następna lekcja: Obrazy](11-obrazy.html)
