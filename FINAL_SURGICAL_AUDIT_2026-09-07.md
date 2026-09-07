# FINAL SURGICAL AUDIT — L&M Technic Energy WEB

Data: 07.09.2026
Gałąź robocza audytu: `FINAL-SURGICAL-AUDIT-WORK-2026-09-07`
Punkt bezpieczeństwa przed audytem: `BACKUP-BEFORE-FINAL-SURGICAL-AUDIT-2026-09-07`

## Zasada audytu
Nie zmieniać `main` ani żadnego zatwierdzonego MASTER-a do czasu przygotowania i przetestowania kompletnego kandydata FINAL.

## P0 — blokery przed MASTER FINAL / domeną

1. **MASTER 009 V7B nie jest jeszcze zintegrowany z produkcyjnym `index.html`.**
   - zatwierdzony MASTER 009 istnieje jako `okno9-v7-test.html` + `assets/contact9-v7.css` + `assets/contact9-v6.js`;
   - produkcyjny `index.html` nadal zawiera wcześniejszą implementację OKNA 9 typu `MASTER GRAPHIC OVERLAY` + `SURGICAL ALIGNMENT V3/V4` i korzysta z `assets/OKNO_9_KONTAKT_MASTER_CLEAN.png`.
   - przed FINAL MASTER trzeba zastąpić produkcyjne OKNO 9 dokładnie zatwierdzonym V7B, bez zmiany MASTER 001–008.

2. **Linki do sklepu nie mają docelowego adresu.**
   - nagłówek `SKLEP` ma `href="#"`;
   - HERO `PRZEJDŹ DO SKLEPU` ma `href="#"`;
   - przycisk sklepu w produkcyjnym OKNIE 9 startuje z `href="#"` i dziedziczy adres z przycisku nagłówka;
   - w dostępnych repozytoriach GitHub nie ma osobnego repo sklepu, więc przed publikacją trzeba wskazać finalny adres sklepu / docelową ścieżkę.

3. **Menu ma nieaktywne pozycje.**
   - `OFERTA` i `PRODUKTY` startują jako `href="#"` i nie są później przepinane przez skrypt;
   - `MAGAZYN`, `LOGISTYKA` i `KONTAKT` są przepinane przez kod OKNA 9 do odpowiednich kotwic.

4. **Centralna dokumentacja MASTER jest niespójna z decyzją właściciela z 07.09.2026.**
   - `README.md`, `MASTER_STATUS.md` i `.master-lock` nadal opisują OKNO 9 jako element roboczy niezamrożony;
   - osobny plik `masters/MASTER-009-OKNO-9-KONTAKT-V7B-FREEZE-2026-09-07.md` poprawnie zapisuje zatwierdzenie MASTER 009.
   - dokumenty centralne trzeba zsynchronizować dopiero razem z kandydatem FINAL.

## P1 — porządek repo po integracji V7B

### Testowe pliki HTML do usunięcia z `main` po zatwierdzeniu FINAL
- `okno9-v6-test.html`
- `okno9-v6b-test.html`
- `okno9-v6c-test.html`
- `okno9-v6d-test.html`
- `okno9-v6e-test.html`
- `okno9-v7-test.html` — usunąć dopiero po przeniesieniu zatwierdzonego V7B do produkcyjnego `index.html`.

### Testowe / stare CSS OKNA 9 do usunięcia po integracji
- `assets/contact9-v6.css`
- `assets/contact9-v6b.css`
- `assets/contact9-v6c.css`
- `assets/contact9-v6d.css`
- `assets/contact9-v6e.css`

`assets/contact9-v6.js` NIE usuwać przed integracją — jest obecnie silnikiem językowym zatwierdzonego V7B. Po integracji można go zachować lub przemianować na nazwę finalną w jednym kontrolowanym kroku.

### Aktywa OKNA 9 wymagające ponownej weryfikacji użycia
- `assets/OKNO_9_KONTAKT_MASTER_CLEAN.png` — produkcyjne stare OKNO 9 nadal go używa; stanie się kandydatem do usunięcia dopiero po integracji V7B.
- `assets/OKNO_9_WAREHOUSE_PHOTO_NATIVE.jpg` — wygląda na pozostałość roboczą; przed usunięciem sprawdzić referencje.
- `assets/OKNO_9_HERO_PHOTO_V7.jpg` — aktywne w V7B, zachować.
- `assets/OKNO_9_WAREHOUSE_PHOTO_V7.jpg` — aktywne w V7B, zachować zgodnie z zaakceptowanym MASTER 009.
- `assets/contact9-v7.css` — aktywne w V7B, zachować.

## P2 — Git / bezpieczeństwo
- na `main` nie ma katalogu `.github/workflows`; stare czerwone workflow są wyłącznie historią;
- repo ma wiele branchy historycznych/backup/MASTER; punktów MASTER/RETURN nie usuwać;
- `main` nie jest chroniony branch protection — przed publicznym FINAL warto rozważyć ochronę ręczną w ustawieniach GitHub.

## P3 — przygotowanie do własnej domeny
Po zatwierdzeniu kandydata FINAL:
- utworzyć `CNAME` dla `www.lmtechnic.eu` lub `lmtechnic.eu` zgodnie z wybraną konfiguracją;
- ustawić DNS domeny;
- włączyć HTTPS;
- dodać docelowe SEO: `meta description`, canonical, Open Graph, favicon;
- dodać `robots.txt` i `sitemap.xml` po ustaleniu finalnej domeny;
- wykonać końcowy test 11 języków i wszystkich CTA po domenie produkcyjnej.

## Kolejność operacyjna FINAL
1. Zintegrować zatwierdzony MASTER 009 V7B z kopią produkcyjnego `index.html` na gałęzi audytu.
2. Naprawić kotwice menu bez zmiany wyglądu MASTER.
3. Wstawić finalny adres sklepu, gdy będzie znany.
4. Usunąć wyłącznie potwierdzone pliki testowe/nieużywane.
5. Zsynchronizować README / MASTER_STATUS / .master-lock.
6. Wdrożyć kandydata audytowego i przetestować na Samsung Galaxy S24 Ultra.
7. Po zatwierdzeniu utworzyć FINAL MASTER całej strony i dopiero wtedy przejść do `lmtechnic.eu`.
