# Dwie kafelki responsive live

Prosty projekt front-end z dwoma wariantami prezentacji produktu opartymi o kafelki i animowane media.

## Co zawiera projekt

1. `index.html` - karuzela 2x2 z materialami wideo/GIF, opisami i rozszerzaniem aktywnego kafla.
2. `index2.html` - wersja z dwoma duzymi kafelkami fullscreen, panelem opisu, przyciskiem CZYTAJ DALEJ i lightboxem.

## Najwazniejsze funkcje

1. Pelna responsywnosc (desktop i mobile).
2. Obsluga klawiatury (Enter, Spacja, Escape).
3. Lazy loading obrazow (`loading="lazy"`).
4. Fallback dla niedostepnych mediow (komunikat zamiast obrazu).
5. Interakcje UI: powiekszanie aktywnego kafla, rozwijanie opisu, podglad grafiki technicznej w lightboxie.

## Struktura plikow

1. `index.html` - wariant karuzeli 2x2.
2. `index2.html` - wariant 2-kafelkowy fullscreen.
3. `bed_close.svg`, `bed_open.svg`, `gear.svg` - ikony naglowkow.
4. `rzut.webp`, `techniczny.png`, `whatermark.png` - grafiki pomocnicze.

## Jak uruchomic lokalnie

1. Otworz folder projektu w VS Code.
2. Uruchom podglad przez Live Server albo otworz bezposrednio `index.html` lub `index2.html` w przegladarce.

## Publikacja na GitHub

Repo lokalne jest gotowe (zainicjalizowane i z pierwszym commitem). Aby opublikowac projekt jako publiczny:

1. Utworz nowe repo na GitHub z widocznoscia Public.
2. Skopiuj URL repo (np. `https://github.com/login/nazwa-repo.git`).
3. W terminalu projektu wykonaj:

```bash
git remote add origin https://github.com/login/nazwa-repo.git
git push -u origin master
```

Jesli chcesz pracowac na branchu `main`, zmien nazwe przed pushem:

```bash
git branch -M main
git push -u origin main
```