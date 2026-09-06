# L&M Technic Energy — WEB

## Status projektu — 06.09.2026

Strona L&M Technic Energy jest budowana metodą **FORWARD ONLY**:

**jeden element → test na Samsung Galaxy S24 Ultra → zatwierdzenie MASTER → zamrożenie → następny element.**

## Aktualny zatwierdzony MASTER

Cała strona od początku do końca **OKNA 8 „PEWNY PARTNER”** jest zatwierdzona i zamrożona.

- zatwierdzony commit strony: `d2d61a3ebed80ed364f5c71d954307dfc224a26b`
- zatwierdzony `index.html` blob SHA: `c292a50a049f9d38744992d03f38edd8c3f2305f`
- stały punkt powrotu: `MASTER-RETURN-POINT-008-OKNO-8-PEWNY-PARTNER-COMPLETE-LIVE-MULTILANGUAGE-2026-09-06`

Zakres zamrożony obejmuje m.in.:
- JĘZYK / LANGUAGE — PL, DE, CZ, SK, AT, CH, NL, BE, LV, DK, EN;
- nagłówek i menu;
- HERO LIVE;
- PELLET DRZEWNY PREMIUM A1;
- OFERTA: WORKI 15 KG, BIG BAG, PELET LUZEM, CAŁA PALETA;
- OKNO 6 — jakość / wydajność / ekologiczne ciepło;
- OKNO 7 — TERMINOWA LOGISTYKA;
- OKNO 8 — PEWNY PARTNER + LIST PREZESA.

## Aktualna praca na `main`

**OKNO 9 „KONTAKT”** jest bieżącym elementem FORWARD ONLY na `main` i nie należy do zakresu zamrożonego, dopóki właściciel nie zatwierdzi go po teście na Samsung Galaxy S24 Ultra.

Podczas pracy nad OKNEM 9 i kolejnymi sekcjami nie wolno zmieniać żadnego elementu zatwierdzonego do końca OKNA 8.

## Aktywne grafiki produkcyjne

W `assets/` pozostają wyłącznie grafiki używane przez bieżącą stronę lub stanowiące zatwierdzone aktywa MASTER:

- `HERO_VISUAL_MASTER_CLEAN.png`
- `WORKI_15KG_VISUAL_MASTER_CLEAN.png`
- `BIG_BAG_VISUAL_MASTER_CLEAN.png`
- `PELET_LUZEM_VISUAL_MASTER_CLEAN.png`
- `paleta_68_worków_pelletu_l_m_technic.png`
- `a_tall_vertical_glossy_promotional_poster_websit.png` — źródło widoku protokołu badań
- `OKNO_6_KAFEL_2_WYSOKA_WYDAJNOSC_MASTER_CLEAN.png`
- `OKNO_6_KAFEL_3_EKOLOGICZNE_CIEPLO_MASTER_CLEAN.png`
- `OKNO_7_KAFEL_1_TRANSPORT_CIEZAROWY_MASTER_CLEAN.png`
- `OKNO_7_KAFEL_2_DOSTAWA_DO_KLIENTA_MASTER_CLEAN.png`
- `OKNO_8_KAFEL_1_PEWNY_PARTNER_MASTER_CLEAN.png`
- `OKNO_8_KAFEL_2_LIST_PREZESA_MASTER_CLEAN.png`
- `OKNO_9_KONTAKT_MASTER_CLEAN.png` — bieżący element roboczy

Dodatkowo główna karta produktu korzysta z `PELLET_MASTER_PRODUCT.jpg` w katalogu głównym.

## GitHub Actions / wdrożenie

Na `main` nie ma własnych plików `.github/workflows/` ani tymczasowych instalatorów chirurgicznych. Wdrożenie strony realizuje standardowy mechanizm **GitHub Pages — pages build and deployment**.

Stare czerwone uruchomienia Actions pozostają jedynie historycznymi zapisami wcześniejszych workflow i nie opisują obecnego drzewa repozytorium.

## Punkty bezpieczeństwa

Nie wolno kasować ani przesuwać gałęzi MASTER / RETURN POINT oraz wskazanych backupów. Najnowszy obowiązujący punkt powrotu to:

`MASTER-RETURN-POINT-008-OKNO-8-PEWNY-PARTNER-COMPLETE-LIVE-MULTILANGUAGE-2026-09-06`

Pełne zasady zamrożenia znajdują się w `.master-lock`, a historia zatwierdzonych etapów w `MASTER_STATUS.md` i plikach `MASTER_RETURN_POINT_*`.

## Zasada produkcyjna

`main` ma zawierać tylko bieżącą działającą stronę, zatwierdzone aktywa MASTER oraz pojedynczy nowy element w trakcie testu. Nie przechowujemy na `main` porzuconych wariantów, plików tymczasowych, nieużywanych duplikatów ani automatycznych instalatorów chirurgicznych.
