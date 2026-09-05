# MASTER STATUS — L&M Technic Energy WEB

Data aktualizacji: **05.09.2026**

## AKTYWNE I ZAMROŻONE MASTER-y

### MASTER 001 — JĘZYK / LANGUAGE
Status: **MASTER — BEZAPELACYJNIE ZATWIERDZONY I ZAMROŻONY**

Obowiązuje zatwierdzony moduł wyboru języka: etykieta `JĘZYK / LANGUAGE`, flaga i nazwa języka, rozwijane menu PREMIUM, zapamiętywanie wyboru oraz wersje PL, DE, CZ, SK, AT, CH, NL, BE, LV, DK i EN.

### MASTER 002 — NAGŁÓWEK + JĘZYK / LANGUAGE
Status: **MASTER — ZATWIERDZONY I ZAMROŻONY**

Obowiązuje zatwierdzony nagłówek L&M Technic Energy, przycisk `SKLEP`, menu oraz proporcje mobilne. Nie wolno go samowolnie zmieniać.

### MASTER 003 — HERO MULTILANGUAGE
Status: **MASTER — BEZAPELACYJNIE ZATWIERDZONY I ZAMROŻONY**

Obowiązuje aktualny przetestowany HERO LIVE: czysta grafika `assets/HERO_VISUAL_MASTER_CLEAN.png` oraz żywe, zmienne językowo: tytuł, opis i CTA. Układ i sposób działania z zatwierdzonego stanu `c9e2ac3cfaca5b6d9be39c5edd85ec2e709bed59` są od tej chwili autorytatywne.

### MASTER 004 — PELLET DRZEWNY PREMIUM A1 MULTILANGUAGE
Status: **MASTER — BEZAPELACYJNIE ZATWIERDZONY I ZAMROŻONY**

Obowiązuje karta produktu z aktywnym tekstem wielojęzycznym i grafiką `PELLET_MASTER_PRODUCT.jpg`.

### MASTER 005 — DZIAŁAJĄCA STRONA LIVE MULTILANGUAGE + OFERTA: WORKI 15 KG + BIG BAG
Status: **MASTER — BEZWZGLĘDNIE ZATWIERDZONY I ZAMROŻONY 05.09.2026 PO TESTACH NA SAMSUNG GALAXY S24 ULTRA**

Autorytatywny stan produkcyjny:
- commit: `c9e2ac3cfaca5b6d9be39c5edd85ec2e709bed59`;
- `index.html` blob SHA: `ed2761a85aabf85aeef6d97d55e8c3d95970c722`;
- HERO: `assets/HERO_VISUAL_MASTER_CLEAN.png`;
- WORKI 15 KG: `assets/WORKI_15KG_VISUAL_MASTER_CLEAN.png`;
- BIG BAG: `assets/BIG_BAG_VISUAL_MASTER_CLEAN.png`;
- silnik językowy działa dla PL, DE, CZ, SK, AT, CH, NL, BE, LV, DK i EN;
- aktywnie zmieniają się: nagłówek/menu, HERO, CTA, karta produktu, nagłówek oferty, tytuły i opisy WORKI 15 KG oraz BIG BAG;
- WORKI 15 KG i BIG BAG używają jednej wspólnej typografii HTML oraz czystych grafik produktowych jako osobnych obrazów;
- obrazy są renderowane bez zoomowania, bez `background-position`, bez masek, bez overlayów i bez Base64.

Ten stan jest od tej chwili wzorcem dla dalszej budowy. Każdy następny element ma być wyłącznie dokładany poniżej lub po aktualnym MASTER-ze, chyba że właściciel wyraźnie nakaże zmianę konkretnego zamrożonego elementu.

---

# MASTER MAPA DALSZEJ BUDOWY — 05.09.2026
Status: **MASTER — ZATWIERDZONA PRZEZ WŁAŚCICIELA PROJEKTU**

Pierwsza grafika strony przesłana przez właściciela 05.09.2026 jest od tej chwili **MASTER MAPĄ DALSZEJ BUDOWY**.

Zasady bezwzględne:
1. Docelowa strona ma być zbudowana jako **aktywna, żywa strona WWW**, a nie jako jeden spłaszczony obraz.
2. Grafiki i układ przedstawione na MASTER MAPIE mają być odtwarzane **1:1 w zatwierdzonych proporcjach**.
3. Budowa odbywa się **jedno okno / jeden kafel naraz**.
4. Asystent przygotowuje i wdraża wyłącznie bieżący element.
5. Właściciel testuje element na Samsung Galaxy S24 Ultra.
6. Dopiero po jednoznacznym zatwierdzeniu element otrzymuje status MASTER / ZAMROŻONE i nie może być zmieniany przy kolejnym kroku.
7. Każdy następny element jest dokładany poniżej już zamrożonego zakresu.

Planowana kolejność według MASTER MAPY:
- OFERTA DOPASOWANA DO TWOICH POTRZEB: WORKI 15 KG → CAŁA PALETA → BIG BAG → PELLET LUZEM;
- DLACZEGO L&M TECHNIC ENERGY?;
- LOGISTYKA DOSTAW;
- JAKOŚĆ POTWIERDZONA BADANIAMI;
- DLA DOMU;
- DLA BIZNESU;
- KONTAKT.

---

# CLEAN START — 05.09.2026
Status: **MASTER — CZYSTA BAZA GIT POTWIERDZONA NA SAMSUNG GALAXY S24 ULTRA**

Przed czyszczeniem utworzono pełny punkt powrotu:
`BACKUP-PRZED-CLEAN-2026-09-05`

Z aktywnej gałęzi `main` usunięto testowy KROK 5, jego stare aktywa i nieaktualne locki. Zachowano nienaruszone MASTER 001–004 oraz ich aktywa. W `index.html` pozostawiono czysty punkt montażowy `#buildRoot`, pod którym będą instalowane kolejne zatwierdzone sekcje.

Stan czystej bazy został dodatkowo zamrożony na gałęzi:
`MASTER-CLEAN-BASE-2026-09-05`

---

# STAŁE MASTER PUNKTY SZYBKIEGO POWROTU

## 001 — CZYSTA BAZA
`MASTER-RETURN-POINT-001-CLEAN-BASE-2026-09-05`

## 002 — HISTORYCZNY STAN PO WORKI 15 KG
`MASTER-RETURN-POINT-002-WORKI-15KG-APPROVED-2026-09-05`

## 003 — DZIAŁAJĄCA STRONA LIVE MULTILANGUAGE + WORKI 15 KG + BIG BAG
Status: **BEZWZGLĘDNIE NIEZMIENNY / 100% PEWNY PUNKT POWROTU**

Nazwa gałęzi:
`MASTER-RETURN-POINT-003-LIVE-MULTILANGUAGE-OFFER-2026-09-05`

Commit referencyjny:
`c9e2ac3cfaca5b6d9be39c5edd85ec2e709bed59`

Zasady:
1. Gałęzi 003 nie przesuwać, nie nadpisywać, nie kasować i nie używać do pracy roboczej.
2. Służy jako natychmiastowy punkt powrotu do działającej i wizualnie zaakceptowanej strony po testach na Samsung Galaxy S24 Ultra.
3. Zawiera działający silnik wielojęzyczny i zatwierdzony stan wizualny przez sekcję WORKI 15 KG + BIG BAG.
4. Każdy następny zatwierdzony cały etap otrzymuje kolejny numerowany punkt powrotu.

---

## ZASADA PRODUKCYJNA
`main` ma zawierać wyłącznie elementy działające i zatwierdzone albo bieżący pojedynczy element przeznaczony do testu. Nie przechowujemy w `main` porzuconych wariantów, błędnych assetów ani konkurencyjnych wersji tego samego kafla.
