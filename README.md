# Markdown od podstaw

Gotowy szkielet samodzielnego kursu Markdown przeznaczonego do publikacji przez GitHub Pages.

## Założenia

- uczestnicy korzystają z Windows, Notatnika i czytnika ekranu;
- kurs nie uczy WordPressa;
- materiał prowadzi od zwykłego tekstu do kompletnego dokumentu;
- przykłady i ćwiczenia są związane z działalnością klubu sportowego;
- strona ma prosty, semantyczny i dostępny układ.

## Struktura repozytorium

- `docs/` — gotowa witryna GitHub Pages;
- `cwiczenia/` — pliki do samodzielnego uzupełnienia;
- `rozwiazania/` — przykładowe rozwiązania;
- `docs/materialy/cwiczenia-markdown.zip` — pakiet do pobrania ze strony.

## Publikacja na GitHub Pages

1. Utwórz publiczne repozytorium na GitHubie.
2. Wgraj całą zawartość tego folderu.
3. Otwórz ustawienia repozytorium.
4. Przejdź do sekcji `Pages`.
5. W części źródła publikacji wybierz publikowanie z gałęzi.
6. Wybierz gałąź `main` i folder `/docs`.
7. Zapisz ustawienia.
8. Po zbudowaniu witryny GitHub poda jej adres.

## Edycja

Treść lekcji znajduje się w plikach `.md` w katalogu `docs`. Każdy plik ma na początku krótki blok metadanych YAML wymagany przez Jekyll.

Przed publikacją warto uzupełnić:

- nazwę autora kursu;
- dane klubu;
- ewentualną licencję;
- prawdziwe przykładowe adresy;
- informacje o sposobie uzyskania pomocy.
