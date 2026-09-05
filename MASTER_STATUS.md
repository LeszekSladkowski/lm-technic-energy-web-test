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

Obowiązuje HERO z aktywnym tekstem wielojęzycznym i grafiką `assets/HERO_MASTER_LM_TECHNIC_ENERGY.png`. Gałąź bezpieczeństwa: `MASTER-KROK-3B-HERO-MULTILANGUAGE`.

### MASTER 004 — PELLET DRZEWNY PREMIUM A1 MULTILANGUAGE
Status: **MASTER — BEZAPELACYJNIE ZATWIERDZONY I ZAMROŻONY**

Obowiązuje karta produktu z aktywnym tekstem wielojęzycznym i grafiką `PELLET_MASTER_PRODUCT.jpg`. MASTER 001–004 nie mogą być naruszane podczas dalszej budowy.

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

Właściciel projektu 05.09.2026 przetestował stronę na Samsung Galaxy S24 Ultra i potwierdził, że baza jest czysta: strona kończy się prawidłowo na zamrożonej karcie `PELLET DRZEWNY PREMIUM A1`, bez starego KROKU 5 i bez uszkodzonych kafli.

Stan czystej bazy został dodatkowo zamrożony na gałęzi:
`MASTER-CLEAN-BASE-2026-09-05`

---

# STAŁY MASTER PUNKT SZYBKIEGO POWROTU 001
Status: **BEZWZGLĘDNIE NIEZMIENNY / 100% PEWNY PUNKT POWROTU**

Nazwa gałęzi:
`MASTER-RETURN-POINT-001-CLEAN-BASE-2026-09-05`

Zasady:
1. Ta gałąź po utworzeniu nie może być przesuwana, nadpisywana, kasowana ani używana do bieżącej pracy.
2. Służy wyłącznie jako pewny, natychmiastowy punkt powrotu do zaakceptowanej i przetestowanej czystej bazy strony.
3. W razie błędu w dalszej pracy można wrócić do niej bez odtwarzania wcześniejszych ustaleń i bez ryzyka dziedziczenia późniejszych błędów.
4. Po każdym następnym **całym oknie**, które właściciel przetestuje i jednoznacznie zatwierdzi jako MASTER, tworzymy kolejny numerowany stały punkt powrotu: 002, 003, 004 itd.
5. Każdy taki punkt ma być traktowany jako historyczny, nienaruszalny kamień milowy.

---

## ZASADA PRODUKCYJNA
`main` ma zawierać wyłącznie elementy działające i zatwierdzone albo bieżący pojedynczy element przeznaczony do testu. Nie przechowujemy w `main` porzuconych wariantów, błędnych assetów ani konkurencyjnych wersji tego samego kafla.
