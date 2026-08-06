# Release Notes

## v1.0.1 - 2026-08-06

Porzadki i przygotowanie repo pod publikacje GitHub Pages.

### Highlights

1. Usunieto stare, nieuzywane pliki i duplikaty mediow z katalogu glownego.
2. Pozostawiono tylko aktywnie uzywane zasoby dla index.html i index2.html.
3. Dodano workflow publikacji do GitHub Pages w .github/workflows/deploy-pages.yml.
4. Uaktualniono README o live linki oraz kroki naprawy 404 (ustawienie Source: GitHub Actions).

## v1.0.0 - 2026-08-04

Pierwsze publiczne wydanie projektu dwie-kafelki-responsive-live.

### Highlights

1. Dwa warianty strony startowej:
- index.html: widok 2x2 z czterema kafelkami i materialami wideo.
- index2.html: wariant fullscreen z dwoma kafelkami, warstwa podgladu i interakcjami.
2. Responsywny uklad dzialajacy na desktopie, tablecie i mobile.
3. Lokalne assety wideo bez koniecznosci korzystania z zewnetrznych URL.
4. Podstawowe wsparcie dostepnosci przez napisy i opisy:
- captions-pl.vtt
- descriptions-pl.vtt

### Assety i multimedia

1. Materialy demo w katalogu assets/videos.
2. Dodatkowe grafiki pomocnicze i placeholdery do szybkiego rebrandingu.

### Uzycie

1. Otworz index.html lub index2.html lokalnie.
2. Zalecane uruchomienie przez lokalny serwer HTTP.

Przyklad:

```bash
python -m http.server 8080
```

Nastepnie:

1. http://127.0.0.1:8080/index.html
2. http://127.0.0.1:8080/index2.html

### Powiazane linki

1. Repozytorium: https://github.com/Stelled40/dwie-kafelki-responsive-live
