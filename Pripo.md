## 01 – historie

- předchůdci byly např. mechanické kalkulátory a logaritmické pravítko

- poté počítače na bázi **relé** (elektro-magnetické spínací prvky)

### 1. generace

- začátek behem 2 sv. války (Atanasoff a Berry, * **von Neumann** * )

- počítače na bázi **elektronek** (zařízení usměrňující a zesilující elektrické signály) – jsou velké a potřebují hodně energie, výrazně hřejí

- velké rozměry počítačů, náročné na údržbu

- I/O – děrné štítky, děrná páska – mechanická záznamová média

- paměť na pevných nevyměnitelných discích

- data uložena na přenosných médiích

- pouze jeden uživatel, nejednotný software 

### 2. generace

- používání **polovodičů** (**tranzistor**, dioda) – nevýhodou je velké množství tepla a časté poškození

- zmenšování a zrychlování počítačů

- velký vývoj magnetických pamětí – zvýšení kapacity

- univerzální programovací jazyky (FORTRAN, COBOL)

### 3.  generace

- na bázi **integrovaných obvodů** – spojené základní elektrické součástky (např. tranzistory)

- zmenšování a zrychlování počítačů

- vniřní paměti, výměnné disky – konec děrných pásek a štítků

- zlepšení výstupu – LED diody, obrazovky

- vyšší programovací jazyky (PASCAL, LISP)

- první osobní počítače

### 4. generace

- miniaturizace integrovaných obvodů, zvyšování výkonu, zlevňování

- mikroprocesory (1971), dynamické paměti, BIOS (Basic Input Output System)

- nová média (FDD, CD, DVD)

- masová výroba

## 02 – elektrické pole

### proud **I** měříme ampérmetrem

**proudová hustota:** σ = I/S (S – průřez vodiče, σ – sigma) výsledek v A, ampérech

### napětí **U** měříme voltmetrem

**intenzita pole:** E = U/L (L – vzdálenost mezi elektrodami) výsledek ve V, voltech – vzniká mezi kladně a záporně nabitými elektrodami

### **elektrický odpor**: vodič se brání toku proudu

R = ρ*L/S (ρ – ró – měrný elektrický odpor – závisí na materiálu vodiče, L – délka vodiče, S – průřez vodiče) výsledek v ohmech Ω

- **Ohmův zákon**: U = R * I (napětí = odpor * proud)

- čím širší vodič (S) tím nižší odpor

- kontakty mohou být i zlaté – aby neoxidovaly

- u kovů odpor při zahřátí stoupá (kvůli výkonu se chladí), u polovodičů při zahřátí odpor klesá (bez chlazení hrozí vyhoření)

**supravodivost** – ochlazení na absolutní nulu – není žádný odpor při přenosu el. energie

**polovodič** – pevná látka, jejíž elektrická vodivost závisí na vnějších (např. dodání tepelné nebo světelné energie) nebo vnitřních (příměs jiného prvku) podmínkách – křemík, germanium, selen

**výkon (příkon) elektrického proudu:** P  =  U * I = R*I2 = U2 / R – výsledek ve W, wattech

**elektrická energie:** W = U*I*t – výsledek v J (Joule) nebo kWh (kilowatthodina)
<br><br>
#### **Kirchhoffův zákon 1**: I1 = I2+I3 – co přitéká, to odtéká – součet proudů v uzlu = 0


#### **Kirchhoffův zákon 2**: U1 – UR2 + U2 – UR1 – UR3 = 0 – součet napětí ve smyčce = 0

- odpory R (správně **rezistor** je pasivní elektrotechnická součástka, která se vyznačuje jedinou vlastností - elektrickým odporem) řadíme paralelně (dle vzorce R=(R1*R2)/(R1+R2)) nebo sériově (sčítají se)

### **kondenzátor**
- vede střídavý proud, kmitočtová vyhybka, dělení kmitočtů – akumuluje energii v podobě elektrostatického pole
- C = ε*S/L (C – kapacita; ε – permitivita – měrná dielektrická vodivost, dána materiálem; S – plocha desek; L – vzdálenost desek) výsledek v F, Faradech
- Q = C*U – energie akumulovaná v kondenzátoru, jednotkou je F, Farad

- víc kondenzátorů vedle sebe zvyšuje kapacitu – řadíme paralelně či sériově

### **tranzistor** 
- je polovodičová součástka, která je základem všech integrovaných obvodů (např. procesorů, pamětí) – rozdělujeme na bipolární (emitor, kolektor, báze) a unipolární (drain, gate, source) – v počítačích se používá zejména pro funkce spínání

**elektronické součástky** –

   **_pasivní_** součástky – nepotřebují zdroj (rezistor, kondenzátor, cívka)

   **_aktivní_** součástky – k činnosti potřebují zdroj napájení (dioda, tranzistor)

   **_diskrétní_** součástky – pouze jedna součástka

   **_integrované obvody_** – pouzdro sdružuje několik diskrétních součástek

dělíme je podle toho, zda zpracovávají spojitý signál (**_analogové obvody_**) nebo diskrétní signál (**_digitální obvody_**) – analogové jsou náchylné na rušení a zkreslení – existují i **_smíšené obvody_** (analogově digitální a digitálně analogové převodníky)

**03 – magnetické pole**

vzniká následkem pohybu elektrických nábojů

elektromagnetické pole – šíří se všude, je problém jej odstínit

elektromagnetická kompatibilita – soulad vzájemně se ovlivňujících vodičů

koaxiál (anténní kabel) – vodič + obalený vodičem –, který ten první odstiňuje

kroucený (TP, twisted pair) – siločáry kroucených kabelů jdou proti sobě a tak se navzájem stíní

**elektromagnetická indukce** – elektrické pole vyvolává (indukuje) pole magnetické -> pole magnetické vyvolává (indukuje) pole elektrické

nestacionární magnetické pole vyvolává ve vodiči (v cívce) indukované napětí a v uzavřeném obvodu indukovaný proud

**magnetická indukce** – síla, kterou magnetické pole působí na pohybující se elektrický náboj – závisí na prostředí

**magnetický indukční tok** – úhrnný tok magnetické indukce procházející určitou plochou – značíme Φ [fí] a jednotkou je Wb, Weber

**magnetomotorické napětí** – značíme Fm a jednotkou je ampér

    pro cívku: Fm = N*I (N – počet závitů)

**intenzita magnetického pole** – vyjadřuje magnetické pole v látce, jednotkou je ampér na metr, A.m-1

**hysterezní smyčka** = princip 0 a 1 v HDD – využívá zbytkový magnetizmus (**remanenci**)

vysvětlení grafu hysterezní smyčky (H je intenzita): začínám v 0 a posílám proud jedním směrem – dochází k magnetizování kovu (směr pravý horní roh, bod A) – po vypnutí proudu zůstane magnetizmus +Br (jih-sever), pokud posílám proud opačným směrem – dochází k magnetizování kovu (směr levý spodní roh, bod B) – po vypnutí proudu zůstane magnetizmus –Br (sever-jih)

**látky dělíme na:**

**diamagnetické** – zeslabují vnější magnetické pole – měď, zlato, stříbro, voda

**paramagnetické** – neudrží magnetizmus – hliník, platina, vzduch

**feromagnetické** – udrží magnetizaci vnějším magnetickým polem – železo, nikl, kobalt, ferity – záznamové vrstvy magnetických médií

**permeabilita** – schopnost materiálu vést magnetický tok – míra magnetizace v důsledku působícího magnetického pole, značí se μ [mí]

**indukované napětí** – napětí vzniklé ve vodiči, který se pohybuje v magnetickém poli (indukované napětí vzniká i tehdy, je-li vodič v klidu a v časově proměnném magnetickém poli) – na principu indukovaného napětí jsou založeny transformátory, elektrické točivé stroje a přenos signálu na dálku

**transformátor** – zařízení, které umožňuje v elektrické síti snižovat / zvyšovat elektrické napětí, je založen na elektromagnetické indukci (využívá indukční zákon)

**04 – číselné soustavy**

součtový zápis a **převod** z libovolné soustavy **do desítkové soustavy**

    (4865)10 = 4 * 103 + 8 * 102 + 6 * 101 + 5 * 100

    (3675)8 = 3 * 83 + 6 * 82 + 7 * 81 + 5 * 80

    (1001101)2 = 1 * 26 + 0 * 25 + 0 * 24 + 1 * 23 + 1 * 22 + 0 * 21 + 1 * 20

                     = 1 * 64 + 0 * 32 + 0 * 16 + 1 * 8 + 1 * 4 + 0 * 2 + 1 * 1 = (77)10

**převod z desítkové** do libovolné **soustavy** – např. do dvojkové (tj. dělíme 2, do osmičkové bychom dělili 8)

 (105)10 : 2 = 52,5

1 (je zbytek po celočíselném dělení)

52 : 2 = 26

0 (nic za desetinou čárkou nemusím oříznout)

26 : 2 = 13

0

13 : 2 = 6,5

1

6 : 2 = 3

0

3 : 2 = 1,5

1

1 : 2 = 0,5

1 (po oříznutí zbyla 0, tj. dále nepokračuji)

zjištěné binární číslo čteme odspodu, tj. 1101001

např. do šestnáctkové

(64091)10 : 16 = 4005

zbytek po celočíselném dělení  = (11)10 neboli (**B**)16

4005 : 16 = 250

(5)10 neboli **5**

250 : 16 = 15

(10)10 neboli **A**

15 : 16 = 0

(15)10 neboli **F**

zjištěné hexadecimální číslo čteme odspodu, tj. FA5B

**převod z binární soustavy do šestnáctkové**

    např. binární číslo 11010011111 rozdělíme po 4 bitech (na NIBLy) a doplníme zleva nulami, tj.

    **0** 1 1 0 **,** 1 0 0 1 **,** 1 1 1 1             zjistíme hodnoty niblů (1 * 23 + 1 * 22 + 1 * 21 + 1 * 20)

      4 2     8     1   8 4 2 1

   6         9        15                  čísla převedeme do šestnáctkové soustavy (15)10 = F

    = 69F                                                                                 a zapíšeme vedle sebe

**převod z binární soustavy do octalové**

    např. binární číslo 10101111 rozdělíme po 3 bitech a doplníme zleva nulami, tj.

    **0** 1 0 **,** 1 0 1 **,** 1 1 1                              zjistíme hodnoty částí (1 * 22 + 1 * 21 + 1 * 20)

      2     4   1   4 2 1

  2       5       7

    = 257                                                                                 a zapíšeme vedle sebe

NIBL – 4 bity – tetráda

MSb – Most significant bite – bit s nejvyšším řádem (nejvíce vlevo)

LSb – Least significant bite – bit s nejnižším řádem (nejvíce vpravo)

**znaménko v binárním kódu**

přímý z něj otočením inverzní (negace) a z něj přičtením jedničky doplňkový

přímý – přidáním znaménkového bitu (na pozici MSb), vzniknou dvě nuly (0000 = +0 a 1000 = -0)

inverzní – kladné je stejné jako v přímém, záporné: znegujeme bity a přidáme 1 na MSb

doplňkový – např. 0101 (+5) zneguju -> 1010 a přičtu 1 (bez přenosu) 1011 = -5

            to platí i obráceně: 1011 -> not = 0100 -> +1 = 0101

**komplement** – otočení 1 a 0, **posun doleva** – násobení 2, **posun doprava** – dělení 2

**05 – logické funkce**

zákony Booleovy algebry (výběr)

komutativní

A+B = B+A                       A×B = B×A

asociativní

A+B+C = A+(B+C) = (A+B)+C         A×B×C = A×(B×C) = (A×B)×C

distributivní

A×(B+C) = A×B+A×C                 A+(B×C) = (A+B)×(A+C)

dvojitá negace – vhodná pro zpoždění signálu

vyloučení třetího

o agresivnosti

A+1 = 1                         A×0 = 0

o neutrálnosti

A+0 = A                         A×1 = A

de Morganovy zákony – převádění sčítání na násobení a opačně

**hradlo** – kombinační logický obvod provádějící jednu z elementárních logických funkcí  – používá se v podobě integrovaných obvodů (tranzistory a další aktivní i pasivní diskrétní součástky)

hradlo **NOT** – logická negace, prohození jedniček a nul

hradlo **AND** – konjunkce, logiský součin Y = A * B

hradlo **NAND** – negované AND

hradlo **OR** – disjunkce, logický součet Y = A + B

hradlo **XOR** – neekvivalence – 1 pokud je A a B rozdílné

hradlo **NOR** – negované OR

počet řádků **pravdivostní tabulky** je 2 na počet vstupních parametrů

**Karnaughova mapa**

postup: z pravdivostní tabulky pracuji s řádky jejichž výsledek je 1 (sloupec Y), v našem případě to jsou označené řádky 1, 2, 4 a 5. Tyto jedničky zanesu do mapy, tak jak na ní napovídají kroužky s číselnými popiskami. Např. řádek 1 – hodnota parametru A je 0, tj. zajímá mě řádek mapy neoznačený A-čárkou (tedy první řádek), dále hodnota parametru B je také 0, tj. zůžím svůj zajem pouze na sloupce mapy neoznačené B-čárkou (tedy první a _poslední_ sloupec prvního řádku) a konečně hodnota parametru C je 1, tj. zůžím svůj zájem pouze na sloupce mapy označené C-čárkou (třetí a _poslední_ sloupec). Tímto způsobem volba padla na _poslední_ sloupec v prvním řádku.

sousední políčka jsou 2 na n, tj. 2,4,8… tj. čtverce nebo obdélníky, mohou se překrývat

pokud mi na stavu nezáleží, značím X

ÚDNF – úplná disjunktivní normální forma – fce zapsaná v základním součtovém tvaru (v pravdivostní tabulce ve sloupci Y mě zajímají řádky s hodnotou 1)

ÚKNF – úplná konjuktivní normální forma – fce zapsaná v základním součinovém tvaru (v pravdivostní tabulce ve sloupci Y mě zajímají řádky s hodnotou 0)

**06 – klopné obvody**

sekvenční logický obvod (výstup závisí na vstupu a předchozím stavu – paměťový efekt) složený z hradel a/nebo aktivních a pasivních diskrétních elektronických součástek

jsou dvoustavové a v jeden okamžik nabývají pouze jednoho stavu – stav mezi je chybou

paměť jednoho bitu – seskupujeme je do registrů (paralelních či sériových)

**registr** – malá a rychlá paměť – skládá se z RS nebo D klopných obvodů

**posuvný regist** = sériově-paralelní převodník – sériově nasunu data a převedu je do paralelní verze a naopak – vhodné pro HW – skládá se z klopných obvodů typu flip-flop

dále např. děliče, čítače (u sčítačky nás zajímá přenos do vyššího řádu, u logického součtu či součinu ne)

**astabilní** – nemá stabilní stav, neustále se přepíná mezi dvěma nestabilními stavy – generátor periodických impulsů, např. hodinových – může být pro přesnost řízeno krystaly – může být rozdílná délka intervalu 1 a 0 (neboli H a L), interval je dán vnitřním zapojením

**monostabilní** – má jeden stabilní stav, po přivedení impulzu napětí se překlopí do druhého stavu a po uplynutí časové kontanty (je dána vnitřním zapojením) se samovolně překlopí zpět do původního stavu – např. automatické vypnutí světla na chodbě

**bistabilní** – může se nacházet ve dvou stabilních stavech, přičemž je možné jej mezi těmito stavy libovolně přepínat – např. paměť (až do přepnutí zůstává v předchozím stabilním stavu) – jsou typickými představiteli sekvenčních logických obvodů

**D** klopný obvod – v okamžiku časového impulzu C (Clock) si zapamatuje stav vstupu D (Data), ten je poté stavem výstupu Q

**RS** klopný obvod – R (Reset) nastaví výstup Q na 0, S (Set) nataví Q na 1; pokud se R=S=1, pak není jisté do jakého setavu se klopný obvod překlopí (označováno jako „hazard“); pokud se R=S=0, pak dochází k paměťovému efektu a výstupem Q je jeho předchozí stav

**JK** klopný obvod – pokud je hodinový pulz (Clock) C=0, pak se bere předchozí stav (paměťový efekt), pokud je C=1, pak je chování stejné jako u RS, tj. J (Jump) nastavuje 1, K (Kill) nastaví 0 a pro J=K=0 se bere předchozí stav, avšak pokud se J=K=1, pak se aktuální hodnota Q neustále mění (překlápí) – používá se např. pro asynchronní čítače

**T** klopný obvod – přepínač paměti – hodnota Q zůstává nezměněna pokud na vstupu T byla 0, mění se při 1

další typy – **latch**, **flip-flop** a **master-slave**

**07 – architektura počítače**

**Architektura dle von Neumanna**

**ALU** (Arithmetic Logic Unit) – provádí aritmetické (např. sčítání, násobení, bitový posun) a logické (např. logický součin, negace) operace

**FPU** (Floating-Point Unit) - jednotka pracující s čísly v pohyblivé řádové čárce

**řadič** – sekvenční obvod – řídí činnost procesoru – vysílá řídící signály (po načtení a dekódování instrukcí) a přijímá stavová hlášení – obsahuje **sadu registrů** (pro uchování operandů a mezivýsledků)

**procesor** (CPU: Central Processor Unit) – integrovaný obvod – řadič + jedna nebo více ALU (a FPU)

**sběrnice** (bus) – propojují jednotlivé bloky a přenášejí data či řídící signály – paralelní a sériové – datová, adresová, řídící nebo napájecí – např. PCI-Express, USB, FireWire, RS-485

**operační paměť** – uchování dat a programů – RWM-RAM paměť – přímo adresovaná procesorem – spojená s procesorem sběrnicí

**cache** – rychlá vyrovnávací paměť umístěná mezi procesor a OP

**vstupní a výstupní zařízení** – vstup a/nebo výstup dat a programů, typické I/O zařízení je disk

**činnost počítače dle von Neumanna**

    zavedení programu a dat do operační paměti pomocí ALU a vstupního zařízení

    ALU provádí podle programu uloženého v OP zpracování dat, mezivýsledky ukládány do OP

    konečné výsledky jsou přes ALU poslány na výstupní zařízení

    pouze jedno CPU + v jeden okamžik se provádí pouze jeden program, který musí být celý v OP

**šířka slova mikroprocesoru –** maximální počet bitů, které je možné zpracovat během jediné operace

**instrukce** – adresa zpracovávané instrukce je uložena v **programovém čítači**

    **_průběh zpracování_**: výběr z OP – dekódování – výpočet reálné adresy – výběr 1. operandu z registru – výběr 2. operandu z registru – provedení operace – zápis výsledku do registru – test přerušení – změna programového čítače

**_instrukční cyklus_**: čas potřebný pro výběr a provedení instrukce            

**_části instrukce_**: operační kód, adresa, data

    **_typy instrukcí_**: přesuny dat (registr-registr, registr-OP a zpět, OP-OP), aritmeticko-logické, posuny a rotace, práce se zásobníkem (zásobník-registr a zpět), skoky (podmíněné / nepodmíněné, smyčka), práce s podprogramy (volání, návrat, podprogramy přerušení), vstup a výstup z/na port, řízení mikroprocesoru (NOP, povolení/blokování přerušení, snížený příkon)

**CISC** – Complex Instruction Set Computer

**RISC** – Reduced Instruction Set Computer

**přerušení** – není nutné se jednotlivých I/O zařízení dotazovat na jejich stav či požadavky (např. stisknutí klávesy, plný disk, chyba na tiskárně – barva, papír), zařízení o nich dá vědět asynchronně = zrychlení počítače

    odskok na obslužný program přerušení provedeme vložením adresy jeho první instrukce do programového čítače – předtím uložíme obsahy registrů a před návratem je obnovíme (používá se paměť typu zásobník)

**DMA** (Direct Memory Access) – přímý přístup do OP bez účasti CPU snižuje nároky na CPU – využívají jej např. grafické, síťové a zvukové karty – zrychluje blokový přenos dat z/do OP

**Harvardská architektura** – existují dvě nezávislé paměti pro data a instrukce (časté využití je u mikrokontrolérů)

**lichá parita** – používá se pro zabezpečení dat v operační paměti – lichý počet jedniček ve slově včetně paritního bitu

**08, 09 – elektronické paměti**

**rozdělení dle přístupu**

    **_RAM_** (Random Access Memory) – libovolný přístup adresováním – matice paměťových buněk

    **_CAM_** (Content Addressable Memory) – asociativní (podle obsahu, např. cache) – realizuje se pamětí RAM

    **_sekvenční_** – např. páska

    **_sériové_** – fronta, posuvný registr (FIFO)

**rozdělení podle určení**

**_vnitřní_**

    **_registry_** – součást řadiče procesoru – klopné obvody

    **_cache_** – vyrovnávací asociativní paměť, realizovaná pomocí SRAM, více úrovní (L1 – v procesoru, L2 –buď v procesoru nebo na základní desce, L3 – na základní desce)

    **_operační paměť_** – typicky DRAM

**_vnější_** – např. HDD, DVD

**parametry** – kapacita, cena za bit, spolehlivost a dále:

    **_přístupová doba_** – za jak dlouho mám na sběrnici data od žádosti

    **_přenosová rychlost_** – šíře toku dat, šíře sběrnice a její taktovací frekvence

    **_statičnost / dynamičnost_** – statické udrží informaci bez obnovování, jsou dražší – dynamická paměť se po čase smaže (i když je pod napětím) musí se tedy periodicky obnovovat

    **_energetická (napěťová) závislost_** – maže se (např. RAM), nemaže se (ROM)

**rozdělení dle schopnosti zápisu**

**RAM-ROM** (zkráceně ROM) – statické, napěťově nezávislé

    **_ROM_** (Read Only Memory) – obsah dán při výrobě (data, ověřené programy)

    **_PROM_** (Programable Read Only Memory) – OTP (One Time Programable, zápis pouze jednou)

    **_EPROM_** (Eraseable Programable Read Only Memory) – mazání UV zářením, obsah udrží několik let

    **_EEPROM_** (Electrically Eraseable PROM) – mazání elektricky buňku po buňce, omezený počet přepsání

    **_Flash EEPROM_** – mazání elektricky po blocích, pro mazání není nutné speciální zařízení, omezený počet přepsání

**RAM-RWM** (Read Write Memory) (zkráceně RAM) – napěťově závislé

**_SRAM_** (Static Random Access Memory) – statická – paměťová buňka je realizována jako bistabilní klopný obvod

**_DRAM_** (Dynamic Random Access Memory) – dynamická – pomalejší ale levnější – nutný periodický refresh (2ms), destruktivní při čtení – informace uložena pomocí elektrického náboje na kondenzátoru

**paměťové moduly** – umožňují volit kapacitu RAM – **_SIMM_** (Single Inline Memory Module) a **_DIMM_** (Dual Inline Memory Module)

**rozdělení dle materiálu a fyzikálních principů**

**_polovodičové_** – využívá vlastností polovodičových tranzistorů (klopné obvody, obvody CMOS)

**_magnetické_** – založené na magnetických vlastnostech materiálu, informaci uchovává směr magnetizace

**_optické_** – využívá optických vlastností materiálu, např. odraz světla

**_ostatní_** – např. feritové (zastaralé) a magnetooptické

**vnější magnetické paměti**

**HDD**

**_přístup k datům_** – posun hlav na cylindr a pootočení ploten na daný sektor (nejmenší adresovatelná jednotka disku, dříve 512 byte nyní 4KB) – způsob adresování cylindr-hlava-sektor (adresování podle geometrie disku) je nahrazen metodou LBA (Logical Block Adressing – sekvenčně číslované sektory bez ohledu na fyzickou strukturu disku)

**_omezená trvanlivost záznamu_** – jednotlivé mikromagnety na HDD nebo FDD postupně časem ztrácí svůj magnetismus a to se poté projevuje jako vadné sektory

**_řadič disku_** – rozhraní mezi „kšandou“ a diskem – určuje rychlost

**_otáčky_** – (5-15tis. za min) čím vyšší, tím kratší přístupová rychlost

přístupová doba (8ms), přenosová rychlost (3 – 320 MB/s), cache (32MB)

fetomagnetická záznamová vrstva je nanesena na paramagnetickou nosnou vrstvu

hlava „plave“ nad plotnou, v běžném režimu stále roztočený – chladí

**_MBR_** (Master Boot Record) – hlavní zaváděcí sektor (512 bytů prvního sektoru disku) – načítá jej BIOS – obsahuje programový kód a tabulku oblastí (Partition Table – informace o umístění a velikosti oblastí) – je zakončen magickým číslem 0xAA55 – zaváděcí sektory jsou také na začátku rozšířené oblasti a každé logické oblasti (o jejich načtení se již ale musí postarat programový kód z MBR)

**_Cluster_** (alokační jednotka ) – cluster je nejmenší logická část souborového systému – většinou zabírá několik sektorů (snaha o snížení režie komunikace s diskem)

**FDD** – pružný kotouč pokrytý feromateriálem, hlava se dotýká média

**CD** – 54x znamená, že je tolikrát rychlejší než standardní audio disk

**10 – zobrazování**

**monitory CRT** (Cathode Ray Tube) – princip katodové trubice – napětí anoda-katoda je přibližně 30000V

**displeje LCD** (Liquid Crystal Display) – dvě desky pokryté elektrodami, mezi nimi se nacházejí tekuté krystaly

**plazmové displeje** – dvě elektrody, mezi nimiž se nachází plyn (směs argonu, xenonu, neonu)

míchání barev probíhá **aditivně R, G, B**

**DAC** – digitálně analogový převodník na grafické kartě