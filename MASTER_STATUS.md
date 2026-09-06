# MASTER STATUS — L&M Technic Energy WEB

Data aktualizacji: **06.09.2026**

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

### MASTER 006 — PELET LUZEM LIVE MULTILANGUAGE
Status: **MASTER — BEZWZGLĘDNIE ZATWIERDZONY I ZAMROŻONY**

Obowiązuje zatwierdzony kafel PELET LUZEM z żywym tekstem wielojęzycznym oraz czystą grafiką `assets/PELET_LUZEM_VISUAL_MASTER_CLEAN.png`.

### MASTER 007 — CAŁA STRONA LIVE DO KOŃCA OKNA 6 / KAFEL 2
Status: **MASTER — 100% ZATWIERDZONY / BEZAPELACYJNIE ZAMROŻONY / BEZWZGLĘDNIE NIEZMIENNY**

Po pełnym teście na Samsung Galaxy S24 Ultra właściciel projektu potwierdził idealne działanie całej aktualnej strony i nadał jej status MASTER.

Autorytatywny zatwierdzony stan kodu strony:
- commit strony: `9c74c3e3a2d8bcaef91a3fe6e6099070226b84d5`;
- `index.html` blob SHA: `d4456c1002a99c5d119e5895a632f33899042adc`;
- stały punkt powrotu: `MASTER-RETURN-POINT-006-OKNO-6-KAFEL-1-2-LIVE-MULTILANGUAGE-2026-09-05`.

Zakres zamrożony obejmuje całą stronę od nagłówka do końca OKNA 6 / KAFEL 2, w szczególności:
- pełny system językowy PL, DE, CZ, SK, AT, CH, NL, BE, LV, DK, EN;
- HERO;
- kartę PELLET DRZEWNY PREMIUM A1;
- kompletną sekcję OFERTA: WORKI 15 KG, BIG BAG, PELET LUZEM, CAŁA PALETA 68 worków;
- OKNO 6 z żywym wielojęzycznym tytułem i opisem;
- KAFEL 1 `POTWIERDZONA JAKOŚĆ A1` z protokołem badań i parametrami;
- KAFEL 2 `WYSOKA WYDAJNOŚĆ` z czystą grafiką `assets/OKNO_6_KAFEL_2_WYSOKA_WYDAJNOSC_MASTER_CLEAN.png` oraz żywym, wielojęzycznym tytułem, opisem i polami parametrów.

Grafika KAFEL 2:
- blob SHA: `e4d018df2f03dd5f5c8e9c7f6f4238cc7c7ed160`;
- rozmiar: `1658006` B.

Od tego miejsca dalsza budowa jest wyłącznie **FORWARD ONLY**. Żaden element MASTER 001–007 nie może zostać zmieniony bez jednoznacznej decyzji właściciela wskazującej konkretny element.

### MASTER 008 — CAŁA STRONA LIVE DO KOŃCA OKNA 6 / KAFEL 3 — EKOLOGICZNE CIEPŁO
Status: **MASTER — 100% SUKCES / BEZWZGLĘDNIE ZATWIERDZONY / BEZAPELACYJNIE ZAMROŻONY / BEZWZGLĘDNIE NIEZMIENNY**

Data zatwierdzenia: **06.09.2026**.

Po pełnym teście na Samsung Galaxy S24 Ultra właściciel projektu potwierdził, że KAFEL 3 oraz cały aktualny zakres strony działają idealnie, w tym poprawne przełączanie języków i poprawne wyświetlanie czystej grafiki KAFEL 3.

Autorytatywny zatwierdzony stan kodu strony:
- website-code commit: `6a255ad0b4d4f4fb2d48e75add1340681742f8dc`;
- `index.html` blob SHA: `54955d596ee3e110f0f4bacc08a14c7f8da76be4`;
- KAFEL 3 grafika: `assets/OKNO_6_KAFEL_3_EKOLOGICZNE_CIEPLO_MASTER_CLEAN.png`;
- grafika blob SHA: `34710198e434a81b9bc32bb35801ea4b40ca1f81`;
- grafika rozmiar: `2764645` B;
- stały punkt powrotu: `MASTER-RETURN-POINT-007-OKNO-6-KAFEL-3-LIVE-MULTILANGUAGE-2026-09-06`.

Zakres MASTER 008 obejmuje całą stronę od góry do końca OKNA 6 / KAFEL 3. W szczególności dodatkowo zamrożone zostają:
- KAFEL 3 `EKOLOGICZNE CIEPŁO`;
- czysta scena graficzna po prawej stronie, bez tekstu językowego w obrazie;
- żywy tytuł i opis HTML;
- trzy żywe pola parametrów;
- pełne przełączanie PL, DE, CZ, SK, AT, CH, NL, BE, LV, DK i EN razem z resztą strony;
- proporcje, układ, typografia, ramki oraz obecny sposób renderowania na Samsung Galaxy S24 Ultra.

Nie wolno ponownie zamieniać KAFEL 3 na spłaszczony plakat, wbudowywać tekstów językowych w grafikę, zmieniać grafiki, proporcji, kadrowania, rozmiaru, układu ani logiki językowej bez jednoznacznego polecenia właściciela dotyczącego właśnie KAFEL 3.

Od tego miejsca dalsza budowa pozostaje wyłącznie **FORWARD ONLY**. Wszystkie elementy MASTER 001–008 są zamrożone.

### AKTUALNE ZAMROŻONE ROZSZERZENIE — CAŁA STRONA DO KOŃCA OKNA 8 „PEWNY PARTNER”
Status: **MASTER / RETURN POINT 008 — 100% SUKCES / ZATWIERDZONE NA SAMSUNG GALAXY S24 ULTRA / BEZWZGLĘDNIE NIEZMIENNE**

Najnowszy autorytatywny zatwierdzony stan strony obejmuje dodatkowo całe OKNO 7 oraz OKNO 8.

- zatwierdzony website-code commit: `d2d61a3ebed80ed364f5c71d954307dfc224a26b`;
- zatwierdzony `index.html` blob SHA: `c292a50a049f9d38744992d03f38edd8c3f2305f`;
- stały punkt powrotu: `MASTER-RETURN-POINT-008-OKNO-8-PEWNY-PARTNER-COMPLETE-LIVE-MULTILANGUAGE-2026-09-06`.

Dodatkowo zamrożone są:
- OKNO 7 `TERMINOWA LOGISTYKA` z grafikami `assets/OKNO_7_KAFEL_1_TRANSPORT_CIEZAROWY_MASTER_CLEAN.png` oraz `assets/OKNO_7_KAFEL_2_DOSTAWA_DO_KLIENTA_MASTER_CLEAN.png`;
- OKNO 8 `PEWNY PARTNER`;
- KAFEL 1 `PEWNY PARTNER` z grafiką `assets/OKNO_8_KAFEL_1_PEWNY_PARTNER_MASTER_CLEAN.png`;
- KAFEL 2 `LIST PREZESA` z grafiką `assets/OKNO_8_KAFEL_2_LIST_PREZESA_MASTER_CLEAN.png`;
- pełne działanie LIVE MULTILANGUAGE oraz zatwierdzone proporcje mobilne.

**OKNO 9 `KONTAKT` jest obecnie pojedynczym elementem roboczym FORWARD ONLY na `main` i nie wchodzi do zamrożonego zakresu do czasu wyraźnego zatwierdzenia przez właściciela.**

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

## 004 — KOMPLETNA OFERTA LIVE MULTILANGUAGE
`MASTER-RETURN-POINT-004-COMPLETE-OFFER-LIVE-MULTILANGUAGE-2026-09-05`

## 005 — KOMPLETNE OKNO OFERTA — 4 KAFLE LIVE MULTILANGUAGE
`MASTER-RETURN-POINT-005-COMPLETE-OFFER-4-CARDS-LIVE-MULTILANGUAGE-2026-09-05`

## 006 — CAŁA STRONA DO KOŃCA OKNA 6 / KAFEL 2
Status: **BEZWZGLĘDNIE NIEZMIENNY / 100% PEWNY PUNKT POWROTU**

Nazwa gałęzi:
`MASTER-RETURN-POINT-006-OKNO-6-KAFEL-1-2-LIVE-MULTILANGUAGE-2026-09-05`

Zatwierdzony commit kodu strony:
`9c74c3e3a2d8bcaef91a3fe6e6099070226b84d5`

Zakres: cała aktualna strona, kompletna OFERTA oraz OKNO 6 z KAFLEM 1 i KAFLEM 2, przetestowane i zatwierdzone na Samsung Galaxy S24 Ultra.

Gałęzi 006 nie wolno przesuwać, nadpisywać, kasować ani używać do pracy roboczej.

## 007 — CAŁA STRONA DO KOŃCA OKNA 6 / KAFEL 3
Status: **BEZWZGLĘDNIE NIEZMIENNY / 100% PEWNY PUNKT POWROTU**

Nazwa gałęzi:
`MASTER-RETURN-POINT-007-OKNO-6-KAFEL-3-LIVE-MULTILANGUAGE-2026-09-06`

Zatwierdzony website-code commit:
`6a255ad0b4d4f4fb2d48e75add1340681742f8dc`

Zakres: cała aktualna strona do końca OKNA 6 / KAFEL 3 `EKOLOGICZNE CIEPŁO`, przetestowana i zatwierdzona na Samsung Galaxy S24 Ultra wraz z działającym systemem językowym.

Gałęzi 007 nie wolno przesuwać, nadpisywać, kasować ani używać do pracy roboczej.

## 008 — CAŁA STRONA DO KOŃCA OKNA 8 „PEWNY PARTNER”
Status: **BEZWZGLĘDNIE NIEZMIENNY / 100% PEWNY PUNKT POWROTU**

Nazwa gałęzi:
`MASTER-RETURN-POINT-008-OKNO-8-PEWNY-PARTNER-COMPLETE-LIVE-MULTILANGUAGE-2026-09-06`

Zatwierdzony website-code commit:
`d2d61a3ebed80ed364f5c71d954307dfc224a26b`

Zakres: cała strona od początku do końca OKNA 8, w tym OKNO 7 `TERMINOWA LOGISTYKA`, OKNO 8 `PEWNY PARTNER` i `LIST PREZESA`, przetestowane i zatwierdzone na Samsung Galaxy S24 Ultra wraz z działającym systemem językowym.

Gałęzi 008 nie wolno przesuwać, nadpisywać, kasować ani używać do pracy roboczej.

---

## ZASADA PRODUKCYJNA
`main` ma zawierać wyłącznie elementy działające i zatwierdzone albo bieżący pojedynczy element przeznaczony do testu. Nie przechowujemy w `main` porzuconych wariantów, błędnych assetów ani konkurencyjnych wersji tego samego kafla.
