# Kulka vs Dziura

Prosta gra na iPhone'a: przechylasz telefon i toczysz metalową kulką, uciekając przed dziurą, która cię goni i z czasem przyspiesza. Wpadniesz — koniec gry. Punkty = sekundy przeżycia. Monety (srebrna 5, złota 10) trafiają na osobne konto widoczne na środku paska. Niebieska kreda zmniejsza dziurę.

## Instalacja na iPhonie (przez GitHub Pages)

1. Utwórz na GitHubie nowe **publiczne** repozytorium, np. `kulka`.
2. Wgraj do niego wszystkie pliki z tego folderu (przez „Add file → Upload files” albo `git push`).
3. W repozytorium: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save**.
4. Po ~1 minucie gra będzie pod adresem `https://<twoj-login>.github.io/kulka/`.
5. Otwórz ten adres w **Safari** na iPhonie → przycisk **Udostępnij** → **Do ekranu początkowego**.
6. Uruchom z ikony, stuknij **Graj** i zezwól na dostęp do **ruchu i orientacji**.

> Czujnik przechyłu na iOS działa tylko przez HTTPS — GitHub Pages to zapewnia.
> Jeśli przypadkiem odmówisz zgody: zamknij aplikację całkowicie i otwórz ponownie.

## Sterowanie

- Pozycja telefonu w chwili stuknięcia **Graj** jest traktowana jako „poziom”.
- Na komputerze (do testów): strzałki na klawiaturze.
