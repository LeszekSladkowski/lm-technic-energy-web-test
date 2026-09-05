# L&M Technic Energy — WEB

## Status projektu — 05.09.2026

Aktywna strona internetowa L&M Technic Energy jest budowana metodą **FORWARD ONLY**: jeden element → test na Samsung Galaxy S24 Ultra → zatwierdzenie MASTER → zamrożenie → następny element.

## Aktualny obowiązujący MASTER

### MASTER 005 — LIVE MULTILANGUAGE + WORKI 15 KG + BIG BAG
Status: **BEZWZGLĘDNIE ZATWIERDZONY I ZAMROŻONY**

Autorytatywny działający stan strony:
`c9e2ac3cfaca5b6d9be39c5edd85ec2e709bed59`

Stały punkt powrotu:
`MASTER-RETURN-POINT-003-LIVE-MULTILANGUAGE-OFFER-2026-09-05`

W tym stanie działają i są zamrożone:
- JĘZYK / LANGUAGE — PL, DE, CZ, SK, AT, CH, NL, BE, LV, DK, EN;
- nagłówek i menu;
- HERO LIVE z żywym wielojęzycznym tytułem, opisem i CTA;
- karta PELLET DRZEWNY PREMIUM A1 z żywym tekstem;
- sekcja OFERTA;
- WORKI 15 KG — żywy tekst + czysta grafika;
- BIG BAG — żywy tekst + czysta grafika.

Aktywne grafiki produkcyjne w `assets`:
- `HERO_VISUAL_MASTER_CLEAN.png`
- `WORKI_15KG_VISUAL_MASTER_CLEAN.png`
- `BIG_BAG_VISUAL_MASTER_CLEAN.png`

## MASTER-y historyczne i punkty bezpieczeństwa

Nie wolno usuwać, przesuwać ani wykorzystywać jako gałęzi roboczych:
- `MASTER-RETURN-POINT-001-CLEAN-BASE-2026-09-05`
- `MASTER-RETURN-POINT-002-WORKI-15KG-APPROVED-2026-09-05`
- `MASTER-RETURN-POINT-003-LIVE-MULTILANGUAGE-OFFER-2026-09-05`
- `MASTER-KROK-1-JEZYK-LANGUAGE`
- `MASTER-KROK-2-NAGLOWEK-LANGUAGE`
- `MASTER-KROK-3B-HERO-MULTILANGUAGE`
- `MASTER-KROK-4-PELLET-MULTILANGUAGE`
- `MASTER-CLEAN-BASE-2026-09-05`
- `BACKUP-PRZED-CLEAN-2026-09-05`

## Zasada produkcyjna

`main` ma zawierać wyłącznie bieżący działający MASTER i pojedynczy nowy element w trakcie testu. Nie przechowujemy w `main` starych wariantów grafik, plików testowych, duplikatów ani porzuconych eksperymentów.

Dalsza budowa odbywa się wyłącznie poniżej / po ostatnim zamrożonym MASTER-ze, chyba że właściciel projektu wyraźnie nakaże zmianę konkretnego zamrożonego elementu.
