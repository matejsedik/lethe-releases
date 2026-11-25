# Zoznam zmien

## 0.12.2 – 2026-11-25

- Automatické aktualizácie sú zapnuté: program má zabudovaný verejný kľúč vydavateľa a prijme len aktualizácie ním podpísané.

## 0.12.1 – 2026-11-25

- Aktualizácie sú chránené digitálnym podpisom vydavateľa: program nainštaluje len verziu podpísanú kľúčom, ktorý je iba u vydavateľa (nestačí ani prístup k jeho účtu na GitHube).

## 0.12.0 – 2026-11-25

- Automatické aktualizácie: program sa (ak to pri prvom spustení povolíte) raz denne pozrie, či je nová verzia, a ponúkne ju. Stiahne ju až po potvrdení, overí jej odtlačok a nainštaluje; rozpracovaná práca ostane. Neodosiela nič z vašich dokumentov.
- Presnejšie skeny: program lepšie číta takmer prázdne strany so sivým zašumeným pozadím (napr. strana s podpismi), a začiernený výsledok takejto strany je čitateľný.
- Na skenoch zachytí aj rodné číslo, dátum narodenia, číslo účtu a e-mail, ktoré OCR prečítalo s chybou (medzera navyše, písmeno namiesto číslice, rozdelená doména).
- Menej zbytočných nálezov: pokazené slová zo skenu („Mcno“, „Zmlun“) sa len navrhnú, obec za zlepeným „vobci“ sa už nepovažuje za meno.

## 0.11.0 – 2026-11-23

- Tmavý režim: v Nastaveniach zvolíte vzhľad Svetlý, Tmavý alebo Podľa Windows. Zmena platí hneď, bez reštartu.
- Zaškrtávacie políčka sú lepšie viditeľné.

## 0.10.1 – 2026-11-23

- Okno Skratky sa otvára bez zvuku Windows.
- Rovnaké medzery medzi stĺpcami a v nich: zoznam dokumentov, náhľad aj nálezy začínajú a končia v jednej rovine a ničoho sa nedotýkajú.

## 0.10.0 – 2026-11-23

- Nový vzhľad: jednotné ikony, farby podľa Lethe (tmavomodré tlačidlo Exportovať), moderné písmo Windows.
- Dokumenty v zozname sú karty s farebným štítkom stavu, nálezy majú farebné bodky a krátky znak stavu (✓ ✗ ?).
- Potvrdiť a Zamietnuť sú výrazné, ostatné tlačidlá menšie.
- Prázdny náhľad radí „Pretiahnite sem zmluvu“, úvodná obrazovka je tmavomodrá a náhľad sa na nález posúva plynulo.

## 0.9.1 – 2026-11-23

- Program sa inštaluje do priečinka „Lethe“.

## 0.9.0 – 2026-11-22

- Program má meno **Lethe** (podľa rieky zabudnutia z gréckych mýtov): v okne, na úvodnej obrazovke, v protokoloch, v inštalátore a v odkazoch na ploche a v ponuke Štart. Priečinok inštalácie a vaše nastavenia ostávajú, aktualizácia sa nainštaluje na pôvodné miesto.

## 0.8.0 – 2026-11-22

- Ručne označené oblasti (aj vyhľadaný text) si môžete pomenovať: dvojklik, F2 alebo pravé tlačidlo → Premenovať.
- Zapnuté kreslenie obdĺžnika je len jemne podfarbené, ikona aj text ostávajú viditeľné.
- Program sa spúšťa bez bliknutia okna cmd, počas načítania ukáže obrazovku „Načítavam…“. Pre príkazový riadok slúži Anonymizer-cli.exe.
- Nová ikona programu: lupa nad začierneným dokumentom.

## 0.7.0 – 2026-11-22

- V PDF program navrhne vložené obrázky (podpis, pečiatka, logo) v skupine „Obrázok (podpis, pečiatka?)“. Sám ich nikdy nezačierni, rozhodujete vy; rovnaký obrázok na viacerých stranách zamietnete naraz.

## 0.6.1 – 2026-11-20

- Príliš veľké alebo poškodené obrázky (tisíce strán, obrovské rozmery) program odmietne namiesto toho, aby zahltil počítač.
- Pri prevode starého Wordu cez Word sa nenasledujú prepojenia na iné súbory ani internet (a vaše nastavenie Wordu sa vráti).

## 0.6.0 – 2026-11-20

- Program spracuje aj obrázky (JPG, PNG, TIFF vrátane viacstranových, BMP), napríklad zmluvu odfotenú mobilom. Výsledok je PDF.
- Starý Word (.doc) a .rtf sa spracujú, ak je nainštalovaný Word alebo LibreOffice. Výsledok je .docx.
- Pri PDF chránenom heslom sa program opýta na heslo. Heslo si nepamätá, uložený výsledok heslo nemá.

## 0.5.0 – 2026-11-20

- Hľadať a začierniť: napíšete text a program ho nájde a začierni na všetkých stranách, aj v iných tvaroch a bez ohľadu na diakritiku.
- Vlastné zoznamy: pravým tlačidlom na nález ho dáte do výnimiek (už sa nenavrhne) alebo do zoznamu „vždy začierniť“. Oba zoznamy sú v nastaveniach.
- Späť a Znova (Ctrl+Z, Ctrl+Y) pre všetky rozhodnutia, obdĺžniky aj vyhľadaný text.
- Pás zmenšených strán so značkami nálezov, filter „Len navrhnuté“ a počet nerozhodnutých nálezov pri každom dokumente.

## 0.4.1 – 2026-11-18

- Odinštalovanie zmaže aj nastavenia a rozpracovanú prácu. Na protokoly sa opýta, či ich ponechať. Tesseract nechá nainštalovaný a upozorní, ako ho odinštalovať ručne.

## 0.4.0 – 2026-11-18

- Začiernený text vo Worde a LibreOffice je čierny pruh približne rovnakej šírky ako pôvodný údaj, takže sa text v dokumente neposúva.
- Keď je v nastaveniach zvolený priečinok výstupu, export uloží súbor rovno tam a nepýta sa znova.
- Protokoly sa ukladajú do priečinka programu `protokoly`, podľa dátumu a zmluvy. Pri opakovanom exporte sa staré protokoly tej istej zmluvy zmažú. Cestu nájdete v nastaveniach.
- Nová voľba: dokumenty Word a LibreOffice uložiť aj ako PDF (potrebný je LibreOffice alebo Word).
- Program už neoznačuje slová ako „Prenajímateľka“ či „Nájomná“ ako mená a nespája meno so slovom z ďalšieho odseku.
- Kontrola celého programu: opravené chyby, odstránený nepoužívaný a zdvojený kód (podrobnosti v docs/SPRAVA_0.4.0.md).

## 0.3.2 – 2026-11-18

- Pri dokumentoch LibreOffice sa odstránia aj odkazy na názvy tabuliek, databáz a podmienky, v ktorých by mohol zostať osobný údaj.

## 0.3.1 – 2026-11-18

- Pri dokumentoch LibreOffice sa z výstupu odstraňujú aj skryté názvy (sekcie, tabuľky, odkazy) a obrázky uložené priamo v texte dokumentu, aby v nich nezostal osobný údaj.

## 0.3.0 – 2026-11-18

- Program spracuje aj dokumenty LibreOffice (`.odt`). Výsledok je opäť `.odt` so začierneným textom.
- Omylom pridaný súbor sa dá odobrať zo zoznamu tlačidlom **Odobrať** alebo klávesom Delete. Tlačidlo **Vyčistiť zoznam** odoberie všetky.
- Po zatvorení a novom spustení sa rozpracované dokumenty aj vaše rozhodnutia vrátia. Uložené sú len cesty k súborom a miesta nálezov, nie samotné údaje. Po uložení začierneného dokumentu sa jeho rozpracovaná práca zabudne.
- Nový nástroj vytvorí skúšobné zmluvy s vymyslenými údajmi (Word a LibreOffice).

## 0.2.3 – 2026-11-18

- Inštalátor, ktorý Tesseract sťahuje z internetu, má v názve „-online“, takže sa neprepíše s bežným inštalátorom.

## 0.2.2 – 2026-11-18

- Inštalátor má Tesseract vždy v sebe, takže inštalácia funguje aj bez internetu.

## 0.2.1 – 2026-11-18

- Inštalátor sa dá zostaviť aj s novým Inno Setup 7 (overené 7.1.1); skript si program nájde sám.

## 0.2.0 – 2026-11-17

- Tesseract (čítanie skenov) sa teraz nainštaluje spolu s programom, ak ho počítač nemá. Slovenčina je súčasťou programu.
- Zoznamy mien, priezvisk a obcí pochádzajú z otvorených údajov (zdroje sú uvedené v súbore THIRD_PARTY_LICENSES.md).
- Vyplnené formuláre a poznámky v PDF sa čítajú a program na ne upozorní. Do výsledného súboru sa neprenášajú.
- Obrázky vo Worde sa očistia od skrytých údajov (poloha, autor, fotoaparát). Upozornenie na obrázky je výraznejšie.
- Pri spracovaní priečinka program na konci oznámi, ktoré súbory preskočil a prečo.
- Doplnené nové kódy bánk.
- Zrozumiteľnejšie chybové hlášky a texty v okne, návode aj protokoloch.
- Pribudol podklad pre právnika (docs/PRE_PRAVNIKA.md).

## 0.1.x

- Dá sa spracovať aj dokument Word (.docx). Údaje sa v ňom nahradia znakmi █ a z výsledného súboru sa odstránia skryté údaje (komentáre, autori, vlastnosti dokumentu).
- Skeny otočené o štvrť, pol alebo tri štvrte otáčky sa rozpoznajú samy.
- Text v dvoch stĺpcoch sa číta správne a meno rozdelené medzi koniec a začiatok strán sa nájde.
- Protokol o začiernení sa dá uložiť aj ako PDF.
- Okno si pamätá nastavenia, tlačidlo Zrušiť zastaví analýzu aj export, ručný obdĺžnik sa dá kresliť z klávesnice.
- Lepšie čítanie skenov (EČV, čísla dokladov, IBAN, e-mail), doplnené kódy bánk.
- Pribudol skript na zostavenie inštalátora.
- Opravený pád pri zmazanom priečinku a výber priečinka výstupu.

## 0.1.0

Úvodné vydanie. Program úplne offline začierňuje osobné údaje v slovenských zmluvách vo formáte PDF (aj v skenoch):
- nájde mená, adresy, rodné čísla, čísla dokladov, bankové účty (IBAN), telefóny, e-maily a ďalšie údaje,
- ukáže náhľad, kde si môžete začiernenie upraviť alebo pridať ručne,
- údaje z výsledného PDF skutočne odstráni (nielen prekryje čiernou plochou),
- vytvorí protokol o tom, čo sa začiernilo,
- funguje v okne aj z príkazového riadka.
