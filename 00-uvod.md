# Úvod ke komentáři zákona č. 365/2000 Sb., o informačních systémech veřejné správy

> **Téma kapitoly:** Tento úvod vymezuje postavení zákona č. 365/2000 Sb., o informačních systémech veřejné správy a o změně některých dalších zákonů (dále „**ZISVS**"), v systému českého práva digitálního státu. ZISVS je **historicky nejstarší obecný kodex eGovernmentu** v ČR — nabyl účinnosti **1. ledna 2001** a od té doby plní roli **rámcového zákona** pro vytváření, správu, provoz, užívání a rozvoj informačních systémů, jimiž stát, územní samospráva a státní právnické osoby vykonávají veřejnou správu. Komentář pokrývá konsolidované znění **ke dni 1. 1. 2026** (publikované jako kód `SB-2000-00365_2026-01-01`), které již reflektuje **přechod gestorské působnosti z Ministerstva vnitra na Digitální a informační agenturu** (dále „**DIA**") k 1. 4. 2023.

---

## 1. Postavení ZISVS v systému českého práva eGovernmentu

ZISVS netvoří samostatný uzavřený regulatorní okruh; je **základní vrstvou** vícevrstvé architektury, kterou tvoří soubor zákonů a podzákonných předpisů upravujících **digitalizaci veřejné správy**. Jeho funkční role spočívá ve čtyřech rovinách:

1. **Definiční rovina** — vymezuje legální pojem **informační systém veřejné správy** (§ 2 odst. 1 písm. b), jeho **správce**, **provozovatele** a **uživatele** a další pojmy (atestace, akreditace, referenční rozhraní, cloud computing, dálkový přístup), na něž odkazují další zákony.
2. **Organizační rovina** — zakotvuje působnost **vlády** (§ 3), **Rady vlády pro informační společnost** (§ 3a), **Digitální a informační agentury** (§ 4) a **orgánů veřejné správy** (§ 5).
3. **Procesní rovina** — upravuje procesy **akreditace** a **atestace** (§§ 6–6f), správu **referenčního rozhraní**, **portálu veřejné správy** (§ 6g), **centrálního místa služeb** (§ 6h), **cloud computingu** (§§ 6i–6z), **kontaktních míst veřejné správy** (Czech POINT, §§ 8a–8b) a vydávání **ověřených výstupů** (§§ 9–9d).
4. **Sankční rovina** — definuje skutkové podstaty **přestupků** (§ 7) a stanoví jejich projednání DIA (§ 7a).

ZISVS tedy plní funkci **rámcového a definičního** zákona, na jehož aparát navazují speciální zákony s konkrétní věcnou působností.

## 2. Vazba na klíčové zákony digitálního státu

ZISVS netvoří uzavřený celek — interpretace jeho jednotlivých institutů vyžaduje **systematický výklad ve spojení s celou rodinou zákonů** o digitálním státě:

| Zákon | Předmět | Vztah k ZISVS |
|---|---|---|
| **z. č. 300/2008 Sb.**, o elektronických úkonech a autorizované konverzi dokumentů (**ZDS**) | datové schránky, autorizovaná konverze | ZISVS zakotvuje obecné účinky podpisu prostřednictvím ISVS (§ 8); ZDS upravuje datové schránky jako prioritní komunikační kanál; portál veřejné správy (§ 6g ZISVS) zajišťuje komunikaci „prostřednictvím datových schránek" |
| **z. č. 111/2009 Sb.**, o základních registrech (**ZZR**) | ROB, ROS, RUIAN, RPP | ZZR je *lex specialis* pro **referenční údaje** základních registrů; ZISVS zakotvuje obecnou koncepci **referenčního rozhraní** (§ 2 odst. 1 písm. i), jehož je systém základních registrů a **eGSB** součástí |
| **z. č. 12/2020 Sb.**, o právu na digitální služby (**ZPDS**) | právo občana na digitální komunikaci, katalog služeb | ZPDS staví na infrastruktuře ZISVS — Portál občana, identita občana, ověřené výstupy z ISVS |
| **z. č. 250/2017 Sb.**, o elektronické identifikaci (**ZEI**) | NIA, kvalifikované systémy elektronické identifikace | ZISVS pracuje s pojmem „**přístup se zaručenou identitou**" (§ 2 odst. 1 písm. u); ZEI implementuje nařízení **eIDAS** |
| **z. č. 297/2016 Sb.**, o službách vytvářejících důvěru pro elektronické transakce | elektronické podpisy, pečetě, časová razítka | provádí **nařízení eIDAS** (910/2014/EU); ZISVS odkazuje na elektronickou identifikaci a doplňkově řeší účinky podpisu prostřednictvím ISVS (§ 8) |
| **z. č. 181/2014 Sb.**, o kybernetické bezpečnosti (**ZKB**) | regulace KII, VIS, poskytovatelů regulované služby | ZISVS § 5b ukládá správcům ISVS, kteří *nejsou* poskytovateli regulované služby podle ZKB, zavádět opatření **v režimu nižších povinností** podle §§ 8, 13 a 14 ZKB |
| **GDPR** — nař. (EU) 2016/679 | ochrana osobních údajů | doplňkový vztah; ZISVS upravuje **provozní (logové) údaje** a zvláštní přístupy (§§ 5d, 5e), aniž by se odchyloval od režimu GDPR |
| **z. č. 134/2016 Sb.**, o zadávání veřejných zakázek (**ZZVZ**) | zadávání VZ | ZISVS na ZZVZ odkazuje u **cloud computingu** (§§ 6i a násl. — pojmy poptávka/nabídka, vertikální/horizontální spolupráce) |
| **z. č. 218/2000 Sb.**, rozpočtová pravidla | dokumentace programů | ZISVS odkazuje na pravidla pro dokumentaci programů obsahujících pořízení / architektonické změny **určených informačních systémů** (§ 3 ZISVS) |
| **z. č. 269/2021 Sb.**, o občanských průkazech | digitální stejnopisy průkazů | ZISVS § 6g odst. 6 — portál veřejné správy poskytuje digitální stejnopisy průkazu prostřednictvím mobilní aplikace |

Z této tabulky je patrné, že ZISVS je **horizontální** zákon — jeho instituty se prolínají napříč všemi sektory veřejné správy (sociální zabezpečení, daně, katastr, obchodní rejstřík, evidence obyvatel, eHealth, justice).

## 3. Klíčové instituty zákona

ZISVS pracuje s několika ústředními pojmy, jejichž porozumění je předpokladem výkladu jednotlivých ustanovení:

- **Informační systém veřejné správy (ISVS)** — funkční celek nebo jeho část zabezpečující cílevědomou a systematickou informační činnost pro účely **výkonu veřejné správy** nebo plnění jiných funkcí státu (§ 2 odst. 1 písm. b). ISVS je provozován **orgánem veřejné správy** (státním orgánem, orgánem ÚSC nebo státní právnickou osobou — § 1 odst. 1). Z působnosti ZISVS jsou taxativně vyňaty utajované systémy, systémy zpravodajských služeb, NBÚ, NÚKIB (§ 1 odst. 2), a s výjimkou vazeb i systémy obrany, krizového řízení, OČTŘ, bezpečnostních sborů, ozbrojených sil, ČNB, FAÚ a vybraných systémů MV, MF a MS (§ 1 odst. 3).
- **Určený informační systém** — kvalifikovaná podmnožina ISVS, která využívá nebo poskytuje služby referenčního rozhraní, má vazbu na takový systém, nebo poskytuje službu **alespoň 5 000 uživatelům ročně** s přístupem se zaručenou identitou (§ 2 odst. 1 písm. v). Pro určené ISVS platí přísnější procesní režim — vyjadřuje se k nim DIA, popř. rozhoduje vláda (§§ 3, 3a, 4, 5).
- **Referenční rozhraní (eGSB / ISSS)** — souhrn právních, technických, organizačních a jiných opatření tvořících **jednotné integrační prostředí** ISVS, které poskytuje kvalitní soustavu společných služeb, včetně výměny oprávněně vyžadovaných informací mezi jednotlivými ISVS i se systémy mimo ČR (§ 2 odst. 1 písm. i). Technickou implementací referenčního rozhraní je dnes **eGSB/ISSS** (eGovernment Service Bus / Informační systém sdílené služby) — komunikační páteř **propojeného datového fondu**. Správcem referenčního rozhraní je DIA (§ 4 odst. 2 písm. d).
- **Centrální místo služeb (CMS)** — soubor technických a programových prostředků, jehož prostřednictvím jsou poskytovány a využívány služby ISVS a propojovány sítě elektronických komunikací (§ 6h odst. 1). Správcem CMS je DIA. Veškerý přístup k referenčnímu rozhraní je možný **výlučně prostřednictvím CMS** (§ 6h odst. 6).
- **Portál veřejné správy (PVS / Portál občana)** — ISVS zajišťující přístup k informacím veřejných orgánů a komunikaci s nimi (§ 6g). Správcem je DIA. Veřejně známou klientskou nadstavbou PVS je **Portál občana** (gov.cz / portal.gov.cz), který zpřístupňuje výpisy z evidencí, datovou schránku, doručování dokumentů a další služby občanům.
- **Czech POINT** (Český podací ověřovací informační národní terminál) — síť **kontaktních míst veřejné správy** (§§ 8a–8b), prostřednictvím kterých se činí podání správním orgánům, doručují dokumenty a vydávají **ověřené výstupy** z ISVS (§§ 9–9d). Kontaktními místy jsou notáři, krajské, matriční a obecní úřady, vybrané zastupitelské úřady, držitel poštovní licence (Česká pošta), Hospodářská a Agrární komora a osoby autorizované DIA (banky, pojišťovny, zdravotní pojišťovny, poskytovatelé univerzální služby). Označení „Czech POINT" je zákonem **vyhrazeno** (§ 8a odst. 5).
- **Akreditace a atestace** — dvoustupňový systém posuzování shody. **Akreditace** osvědčuje předpoklady k provádění atestací (§§ 6–6a); provádí ji „akreditující osoba" pověřená DIA. **Atestace** ověřuje **dlouhodobé řízení** ISVS s požadavky zákona; provádí ji **atestační středisko** pověřené DIA (§§ 6b–6f). Orgány veřejné správy si atestaci dlouhodobého řízení musí zajistit a prokázat ji **atestem** (§ 5a odst. 4) — povinnost se nevztahuje na obce v základním rozsahu přenesené působnosti.
- **Národní architektura veřejné správy / informační koncepce ČR** — strategický dokument na **5 let**, který stanoví cíle ČR v oblasti ISVS a obecné principy jejich pořizování, vytváření, správy, provozování, užívání a rozvoje (§ 5a odst. 1). Schvaluje jej vláda na návrh Rady vlády pro informační společnost. Orgány veřejné správy na něj navazují vlastními **informačními koncepcemi orgánu veřejné správy** (§ 5a odst. 2).
- **Cloud computing veřejné správy / eGovernment Cloud** — sektorový kodex (HLAVA VI, §§ 6i–6z) zakotvující dvouvrstvou architekturu: **státní cloud** (provozovaný poskytovatelem státního cloud computingu pověřeným vládou) a **komerční cloud** (poskytovaný osobami zapsanými v **katalogu cloud computingu**, který spravuje DIA). Cloud do nejvyšší bezpečnostní úrovně smí poskytovat pouze státní poskytovatel (§ 6m odst. 2). Bezpečnostní úrovně stanoví vyhláška NÚKIB (§ 12 odst. 2 písm. g).
- **Přestupky** (§ 7) — sankce do **10 000 000 Kč** za nejtěžší přestupky (přestupek poskytovatele cloud computingu / orgánu veřejné správy v oblasti cloudu), do 1 000 000 Kč pro středně závažné a do 100 000 / 200 000 Kč pro méně závažné. Projednává **DIA** (§ 7a).

## 4. Digitální a informační agentura (DIA) jako nový gestor

Klíčovou systémovou změnou poslední doby je vznik **Digitální a informační agentury** (DIA) na základě **zákona č. 471/2022 Sb.**, **s účinností od 1. dubna 2023**. DIA je **ústřední správní úřad** pro **digitalizaci a informační systémy veřejné správy**, který převzal podstatnou část působnosti, kterou předtím vykonávaly:

- **Ministerstvo vnitra** — gestor ZISVS, ZDS, ZZR, ZEI a Czech POINT od přijetí těchto zákonů;
- **Národní agentura pro komunikační a informační technologie (NAKIT)** — provoz CMS a vybraných ISVS;
- **Odbor hlavního architekta eGovernmentu** (OHA) — koordinace architektury.

Po novele z roku 2023 ZISVS důsledně používá legislativní zkratku **„Agentura"** (definovanou v § 2 odst. 1 písm. r) jako synonymum pro **DIA**. Touto změnou byla **odštěpena agenda eGovernmentu** od bezpečnostní agendy MV a vytvořen specializovaný úřad s mandátem pro **architektonický a koncepční rozvoj** digitálního státu, **akreditaci a atestace**, správu **referenčního rozhraní** a **CMS**, regulaci **cloud computingu** veřejné správy, vedení **katalogu cloud computingu** a koordinaci **Czech POINTu**. Vrcholné architektonické otázky zůstávají v gesci vlády a její **Rady vlády pro informační společnost** (§ 3a).

## 5. Vztah k unijnímu právu

ZISVS reflektuje několik unijních režimů:

- **nařízení eIDAS** (910/2014/EU) — elektronická identifikace, služby vytvářející důvěru. ZISVS na něj odkazuje pojmem „kvalifikovaný systém elektronické identifikace" (§ 2 odst. 1 písm. u);
- **GDPR** (2016/679) — ochrana osobních údajů; ZISVS rezervuje **mlčenlivost** o záznamech o zvláštních přístupech (§ 5d) ve prospěch národní bezpečnosti, vyšetřování trestné činnosti a ochrany hospodářských zájmů ČR a EU (typický „security exception" GDPR);
- **směrnice NIS 2** (2022/2555) — kybernetická bezpečnost; transponována ZKB; ZISVS § 5b zakotvuje minimální opatření pro správce ISVS, kteří *nejsou* poskytovateli regulované služby podle ZKB;
- **nařízení o jednotné digitální bráně** (2018/1724) — Single Digital Gateway; portál veřejné správy (§ 6g) zajišťuje českou národní vrstvu;
- **směrnice o opakovaném použití informací veřejného sektoru** (2019/1024) — Open Data; ZISVS doplňuje **z. č. 106/1999 Sb.**

## 6. Novelizace a vývoj zákona

ZISVS prošel od svého přijetí (zákon č. 365/2000 Sb. — schválený 14. září 2000) **více než 20 novelami**. K nejvýznamnějším patří:

- **z. č. 81/2006 Sb.** — zavedení **Czech POINTu**;
- **z. č. 130/2008 Sb.** — širší koncepce **referenčního rozhraní**, vazba na ZDS;
- **z. č. 261/2014 Sb.** — kontaktní místa veřejné správy, „osoba autorizovaná Ministerstvem vnitra";
- **z. č. 192/2016 Sb.** — registr smluv, vazba ISVS na ZRS (z. 340/2015 Sb., **z. č. 340/2015 Sb.**);
- **z. č. 110/2019 Sb.** — adaptace na **GDPR**;
- **z. č. 12/2020 Sb.** — provazba na právo na digitální služby;
- **z. č. 261/2021 Sb.** — zavedení kapitoly o **cloud computingu** (HLAVA VI);
- **z. č. 471/2022 Sb.** — vznik **DIA**, přechod gestorské působnosti z MV na DIA k 1. 4. 2023;
- **z. č. 152/2023 Sb.** a další novely 2023–2025 — terminologická adaptace, rozvoj agendy cloud computingu, propojený datový fond, digitální stejnopisy průkazů.

## 7. Účinnost

ZISVS byl vyhlášen 30. listopadu 2000. Hlavní účinnost nastala **dnem vyhlášení** (s výjimkou některých technicky náročných ustanovení odložených na 1. 1. 2001, 1. 7. 2001, 1. 1. 2002 — § 14). Účinnost komentovaného **konsolidovaného znění** je **1. ledna 2026** (kód `SB-2000-00365_2026-01-01`).

## 8. Cíl a struktura komentáře

Komentář pokrývá **úplné** znění ZISVS — všech 14 paragrafů Části první (s litery § 3a, § 5a–§ 5e, § 6a–§ 6z, § 7a, § 8a–§ 8b, § 9a–§ 9e), Část druhou (změnový zákon o správních poplatcích, § 12), Část třetí (změna kompetenčního zákona, § 13) a Část čtvrtou (Účinnost, § 14). Členění komentáře sleduje **systematiku zákona**; výklad je veden tak, aby u každého paragrafu byl vykládán **doslovný text** v blockquote citátu, na nějž navazuje **substantivní výklad** s odkazem na judikaturu, soustavné a teleologické argumenty a srovnání se souvisejícími předpisy. Cílem je poskytnout aplikační vodítko pro **správce a provozovatele ISVS** (orgány veřejné správy, jejich smluvní partnery, atestační střediska, poskytovatele cloud computingu) i pro **interpreta** zákona (advokáta, soudce, akademika), který se ZISVS zabývá v širším kontextu **digitálního státu**.
