# PlotVenture

**PlotVenture** to prosta aplikacja front-endowa pozwalająca użytkownikom wybrać tło strony, ocenić aplikację, dodać i przeszukiwać opinie oraz wyświetlać aktualny zegar na żywo.

## Funkcjonalności

- Wybór tła (zapamiętywany w localStorage)
- System ocen 1-5 gwiazdek (localStorage)
- Dodawanie i wyświetlanie opinii użytkowników (localStorage)
- Wyszukiwanie opinii po tekście
- Zegar na żywo aktualizowany co sekundę
- Pobieranie opinii do pliku tekstowego
- Resetowanie lokalnych danych użytkownika

## Jak uruchomić lokalnie?

1. Pobierz plik `index.html` z repozytorium.
2. Otwórz go w dowolnej nowoczesnej przeglądarce (np. Chrome, Firefox).
3. Korzystaj bez żadnego backendu — wszystko działa lokalnie.

## Jak opublikować na GitHub Pages?

1. Stwórz nowe repozytorium na GitHub o nazwie np. `plotventure`.
2. Skopiuj plik `index.html` oraz `README.md` do repozytorium.
3. W ustawieniach repozytorium wybierz **Pages**.
4. Jako źródło wybierz gałąź `main` (lub `master`) i folder root `/`.
5. Zapisz zmiany.
6. Po chwili Twoja aplikacja będzie dostępna pod adresem:  
   `https://TwojaNazwaUzytkownika.github.io/plotventure/`

## Automatyzacja publikacji z GitHub Actions

Repozytorium posiada prosty workflow GitHub Actions, który przy każdym pushu na gałąź `main` automatycznie publikuje zawartość do GitHub Pages.

---

## Struktura repozytorium

- `index.html` — główny plik aplikacji
- `README.md` — ten plik
- `.github/workflows/deploy.yml` — workflow CI/CD do automatycznej publikacji

---

## Kontakt

Masz pytania lub sugestie? Napisz do mnie!

---

## Licencja

MIT License
