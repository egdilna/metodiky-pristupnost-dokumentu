---
title: Metodika pro přístupnost dokumentů
author: egdílna.cz
status: Platné
Version: 1.1
date: 2022-08-04
subtitle: Metodický dokument pro splnění povinnosti přístupnosti dokumentů veřejnoprávních původců
---

© 2022 EGdílna.cz, volná licence CC

OBSAH DOKUMENTU

- [1. Úvod](#1-úvod)
  - [1.1. Účel a použití metodiky](#11-účel-a-použití-metodiky)
  - [1.2. Publikace metodiky a připomínky](#12-publikace-metodiky-a-připomínky)
  - [1.3. Historie verzí](#13-historie-verzí)
  - [1.4. Významy některých technických pojmů](#14-významy-některých-technických-pojmů)
- [2. Přístupnost dokumentů](#2-přístupnost-dokumentů)
  - [2.1. Co je přístupnost dokumentů a proč to řešit?](#21-co-je-přístupnost-dokumentů-a-proč-to-řešit)
  - [2.2. Přístupný dokument a nepřístupný dokument](#22-přístupný-dokument-a-nepřístupný-dokument)
    - [2.2.1. Co je to vlastně přístupný dokument a jak se s ním dá pracovat](#221-co-je-to-vlastně-přístupný-dokument-a-jak-se-s-ním-dá-pracovat)
    - [2.2.2. Technické charakteristiky a vlastnosti přístupného dokumentu](#222-technické-charakteristiky-a-vlastnosti-přístupného-dokumentu)
      - [2.2.2.1. Textová reprezentace](#2221-textová-reprezentace)
      - [2.2.2.2. Vyhledatelný text](#2222-vyhledatelný-text)
      - [2.2.2.3. Značky struktury dokumentu a správné pořadí čtení](#2223-značky-struktury-dokumentu-a-správné-pořadí-čtení)
      - [2.2.2.4. Alternativní textové popisy pro netextové prvky](#2224-alternativní-textové-popisy-pro-netextové-prvky)
      - [2.2.2.5. Písma, která umožňují extrahovat znaky do textu](#2225-písma-která-umožňují-extrahovat-znaky-do-textu)
      - [2.2.2.6. Interaktivní pole s popisky formulářů s přístupnými chybovými zprávami a bez načasování](#2226-interaktivní-pole-s-popisky-formulářů-s-přístupnými-chybovými-zprávami-a-bez-načasování)
      - [2.2.2.7. Další interaktivní funkce: Hypertextové odkazy a navigační pomůcky](#2227-další-interaktivní-funkce-hypertextové-odkazy-a-navigační-pomůcky)
      - [2.2.2.8. Jazyk dokumentu a jednoznačný název](#2228-jazyk-dokumentu-a-jednoznačný-název)
      - [2.2.2.9. Zabezpečení, které nebude zasahovat do přístupnosti](#2229-zabezpečení-které-nebude-zasahovat-do-přístupnosti)
      - [2.2.2.10. Ostatní charakteristiky a funkce zpřístupnění dokumentu](#22210-ostatní-charakteristiky-a-funkce-zpřístupnění-dokumentu)
  - [2.3. Přístupnost dokumentů v kontextu spisové služby a správy dokumentů](#23-přístupnost-dokumentů-v-kontextu-spisové-služby-a-správy-dokumentů)
    - [2.3.1. Spisová služba jako odborná správa dokumentů](#231-spisová-služba-jako-odborná-správa-dokumentů)
    - [2.3.2. Druhy a formy dokumentů a jejich správy](#232-druhy-a-formy-dokumentů-a-jejich-správy)
    - [2.3.3. Způsoby vzniku vlastního dokumentu](#233-způsoby-vzniku-vlastního-dokumentu)
  - [2.4. Legislativní rámec](#24-legislativní-rámec)
  - [2.5. Povinnost vytvářet přístupné dokumenty](#25-povinnost-vytvářet-přístupné-dokumenty)
  - [2.6. Práce s přístupným dokumentem a přínosy přístupnosti](#26-práce-s-přístupným-dokumentem-a-přínosy-přístupnosti)
  - [2.7. Důsledky nesplnění přístupnosti dokumentů](#27-důsledky-nesplnění-přístupnosti-dokumentů)
- [3. Jak na to](#3-jak-na-to)
  - [3.1. Zahrnutí přístupnosti dokumentů do správy dokumentů a procesů](#31-zahrnutí-přístupnosti-dokumentů-do-správy-dokumentů-a-procesů)
  - [3.2. Náležitosti dokumentů](#32-náležitosti-dokumentů)
    - [3.2.1. Obsahové náležitosti](#321-obsahové-náležitosti)
    - [3.2.2. Technické a procesní náležitosti dokumentu](#322-technické-a-procesní-náležitosti-dokumentu)
  - [3.3. Přístupnost u druhů a forem dokumentů](#33-přístupnost-u-druhů-a-forem-dokumentů)
    - [3.3.1. Přístupnost pro digitální dokumenty](#331-přístupnost-pro-digitální-dokumenty)
      - [3.3.1.1. Pro dokumenty generované informačními systémy](#3311-pro-dokumenty-generované-informačními-systémy)
      - [3.3.1.2. Pro dokumenty vytvářené v editorech](#3312-pro-dokumenty-vytvářené-v-editorech)
      - [3.3.1.3. Pro dokumenty doručené od jiného původce](#3313-pro-dokumenty-doručené-od-jiného-původce)
      - [3.3.1.4. Možnost odeslat dokument také v jiném formátu](#3314-možnost-odeslat-dokument-také-v-jiném-formátu)
    - [3.3.2. Jak má správně vypadat analogová verze dokumentu, aby šla zpracovat asistivní technologií](#332-jak-má-správně-vypadat-analogová-verze-dokumentu-aby-šla-zpracovat-asistivní-technologií)
    - [3.3.3. Přístupnost u dynamických druhů dokumentů](#333-přístupnost-u-dynamických-druhů-dokumentů)
  - [3.4. Co je nepřípustné a co nikdy nedělat](#34-co-je-nepřípustné-a-co-nikdy-nedělat)
# 1. Úvod

## 1.1. Účel a použití metodiky

Tento metodický dokument slouží veřejnoprávním původcům pro lepší pochopení a také jako návod na splnění povinnosti tzv. přístupnosti dokumentů. Protože jde o technickou oblast, která vyžaduje hluboké technické znalosti, ukazuje se nezbytným původcům v této oblasti pomoci.

Dokument je určen dvěma hlavním skupinám uživatelů:

- Manažerům v organizacích původců: V tomto dokumentu se vysvětluje, co je to přístupnost dokumentů, proč ji řešit, jak pomáhá nejen osobám se zdravotním postižením a se specifickými potřebami, především však, na co nezapomenout a jak do toho. Manažer pak bude vědět, co po kom chtít, aby povinnosti byly řádně splněny.
- Odborným a technickým pracovníkům: Tento dokument obsahuje i podrobné technické a procesní informace o přístupnosti digitálních dokumentů, o jednotlivých formátech a jejich podrobných specifikacích a o jejich řešení. Metodici a manažeři spisové služby, ale i IT pracovníci, se v něm dozvědí, co konkrétně musejí zajistit, aby jejich dokumenty v digitální podobě splňovaly veškeré technické požadavky na jejich přístupnost.

## 1.2. Publikace metodiky a připomínky

Veškeré podrobnosti, a to včetně předchozích verzí, pracovních podkladů a poznámek a také seznamu a stavu připomínek, lze nalézt v otevřeném GIT repozitáři [GitHub - egdilna/metodiky-pristupnost-dokumentu: Metodiky pro přístupnost digitálních dokumentů...](https://github.com/egdilna/metodiky-pristupnost-dokumentu)

Aktuální verze je k dispozici vždy na následujících URL adresách:

Webová verze metodiky k náhledu a čtení

- [<https://github.com/egdilna/metodiky-pristupnost-dokumentu/blob/main/Metodika-pristupnost-dokumentu.md>](https://github.com/egdilna/metodiky-pristupnost-dokumentu/blob/main/Metodika-pristupnost-dokumentu.md)

Ke stažení v otevřeném editovatelném formátu

- [https://github.com/egdilna/metodiky-pristupnost-dokumentu/raw/main/metodika-pristupnost-dokumentu.docx](https://github.com/egdilna/metodiky-pristupnost-dokumentu/raw/main/metodika-pristupnost-dokumentu.docx)

Jakékoliv připomínky či dotazy a návrhy na změny a doplnění lze přidávat vytvořením nového Issue v repozitáři, kde lze také sledovat postup prací a již vytvořené Issues, a to [v sekci Issues v repozitáři](https://github.com/egdilna/metodiky-pristupnost-dokumentu/issues)

## 1.3. Historie verzí

Toto je verze 1.1 vydaná v srpnu 2022.

| Verze | Kdy | Popis změn |
|----|------|--------------|
| 1.0 | 4/2022 | První public draft publikovaný jako již použitelný a nasaditelný do praxe. |
| 1.1 | 8/2022 | Kapitola 2.4 s legislativním rámcem rozdělena na dvě podkapitoly a zejména přidána podkapitola [2.4.2. Závazné normy] kde jsou odkazy na obě ISO závazné normy týkající se přístupnosti a PDF/a. |

## 1.4. Významy některých technických pojmů

Kromě obecně používaných pojmů z oblasti spisové služby, má přístupnost dokumentů několik vlastních odborných termínů, které se v tomto dokumentu používají a u kterých musí čtenář dobře znát jejich význam:

- Přístupnost dokumentů: Část schopnosti úřadu Správa dokumentů, která zajistí, aby každý dokument vzniklý z vlastní činnosti úřadu byl přístupný (definuje význam a potřeba pojmu)
- Přístupný dokument: Dokument, s jehož obsahem se může seznámit kdokoliv, tedy i osoba se zdravotním postižením, a to bez nutnosti dodatečného zpracování obsahu dokumentu způsobem, k němuž nebyl dokument určen. (definuje význam a potřeba pojmu)
- Textová reprezentace: V rámci každého dokumentu se používá logický strom značených struktur, který poskytuje smysluplné pořadí čtení obsahu a také metodu pro definování role strukturálních prvků a vztahu k obsahu stránky. V rámci této struktury značek lze poskytnout další vlastnosti, jako je alternativní text a náhradní text. (definuje překlad ISO specifikací)
- Kontejner dokumentu: Technická část datového souboru digitálního dokumentu obsahující jednu či více komponent obsahu dokumentu, nebo komponent a jejich textových vrstev (definuje překlad ISO specifikací)
- Textová vrstva: Reprezentace veškerého významového obsahu dokumentu formou prostého textu a jeho speciálních atributů, aby bylo možno reprezentovat jakýkoliv obsah a jeho druh a význam pouhým čtením prosté textové informace (definuje překlad ISO specifikací)
- Tagovaný obsah: Textová vrstva obsahu dokumentu, která kromě samotného textu obsahuje i jeho speciální atributy, ze kterých je zřejmé, o jaký typ obsahu se jedná a jaký je jeho význam (definuje překlad ISO specifikací)

# 2. Přístupnost dokumentů

Následuje znalostní a teoretická část, ve které se dozvíte, co je to přístupnost dokumentů a že jde o nezpochybnitelnou povinnost. Také se dozvíte konkrétní přínosy, abyste pochopili, proč je to tak důležité.

## 2.1. Co je přístupnost dokumentů a proč to řešit?

Přístupnost dokumentů je jednou ze základních schopností všech úřadů a organizací, jež jsou podle zákona veřejnoprávními původci, a tedy  spravují a vytvářejí dokumenty. Fakticky se jedná o způsob technické tvorby dokumentů tak, aby se s jejich obsahem a strukturou mohli plně seznámit a plně s nimi pracovat skutečně všichni uživatelé, a to včetně osob se zdravotním postižením či jiným funkčním omezením.

Je důležité si v této souvislosti uvědomit několik podstatných věcí:

1. Vytvářet přístupné dokumenty je i stávající povinnost zakotvená v legislativě ke spisové službě, ale úřady tuto povinnost často ignorují.
2. I stávající dokument úřadu, pokud není přístupný, není právně platný, neboť vznikl v rozporu se zákonem, protože nemá řádné technické náležitosti.
3. Podařilo se, i přes dosavadně dostačující úpravu, aktualizovat konkrétní technické povinnosti přístupných dokumentů.
4. Určitým způsobem, (ale ne zcela), to souvisí s WMAA, kdy jde o jistou formu obsahu.
5. V roce 2022 bude na tuto oblast zaměřena pozornost, bude i součástí atestací elektronických systémů spisových služeb (ESSL) a budou tvořeny metodiky a technické templaty.

## 2.2. Přístupný dokument a nepřístupný dokument

Je důležité co nejlépe porozumět tomu, jaký dokument je a není přístupný. Přístupné dokumenty jsou sice povinnost, ale především je to nutnost. Pro uživatele je totiž řádně čitelný jen přístupný dokument.

### 2.2.1. Co je to vlastně přístupný dokument a jak se s ním dá pracovat

Přístupný dokument je digitální dokument, který je technicky vytvořen tak, že s ním a s jeho obsahem může pracovat kdokoliv, a to včetně osob se zdravotním postižením. Ti totiž potřebují pracovat s textem jeho obsahu. Dokument kupříkladu ve formátu PDF nemusí být totiž přístupný jen proto, že je v PDF. To, co vidí běžný uživatel na obrazovce, totiž může být jen obrazová informace, nikoliv text ve strojově čitelném formátu. Představte si to tak, jako kdybyste se pokusili editovat v textovém editoru pouhý obrázek textu. Nemůžete ho upravovat, ani text z něj zkopírovat do jiného dokumentu. A přesně takto technicky funguje práce s textovým obsahem přístupného dokumentu. Uživatelé, kteří text nevidí, si jej musí nechat přečíst buď počítačovým hlasem, nebo na braillském řádku braillovým písmem. Pokud je dokument vytvořen správně, tak se s jeho obsahem může takový uživatel seznámit jako ostatní, ale kdokoliv si z textu dokumentu může i cokoliv zkopírovat či poznamenat. Zkrátka, nepracuje s obrazem viditelným na obrazovce, ale s textem jako v textovém editoru. Formát PDF/a navíc zajistí, že s obsahem dokumentu nikdo nemůže manipulovat a v textu něco změnit. Uživatel vždy věří obsahu textové vrstvy, a proto je zásadní požadavek na shodu obrazu s textem.

Jak se s přístupným dokumentem pracuje? Běžný uživatel s ním pracuje zcela klasicky jako s jakýmkoliv jiným dokumentem, nicméně může využívat výhody, jako je hledání v textu, možnost si část textu označit a zkopírovat či si dokument nechat číst nahlas umělým hlasem (to se hodí zejména u delších dokumentů a elektronických knih). Také informační systémy a aplikace mohou těžit z toho, že dokument obsahuje strojově čitelný text, a tak lze v takových dokumentech třeba i indexovat, nebo prohledávat celé složky na konkrétní text.

Uživatel s nějakým zdravotním postižením (většinou se pochopitelně jedná o nevidomé či slabozraké) používá tzv. \"Asistivní technologie\", tedy software schopný text číst umělým hlasem či zobrazit na braillském řádku. Nebo software umožňující úpravu obrazu (zvětšit a zvýraznit text, obrátit barvy, apod.). Takzvané odečítače obrazovky zprostředkovávají jakýkoliv textový obsah viditelný na obrazovce, tedy i text dokumentu. Zatímco třeba na webových stránkách či v textovém editoru to není problém, u procházení digitálního dokumentu v PDF záleží právě na tom, jestli dané PDF má textovou reprezentaci a textovou vrstvu. Bez ní se jedná jen o obrazové PDF a to z principu čitelné není. S textovou vrstvou ale uživatel prochází text dokumentu jako na webové stránce, a to včetně případných odkazů, nadpisů, částí a popsaných obrázků. Uživatel asistivních technologií může dokumentem procházet, číst jednotlivá slova, věty či celé odstavce, rychle se přesouvat mezi částmi textu, nadpisy, odkazy, formulářovými prvky a dalším typem obsahu. Pro něj je to tak jediná cesta, jak s takovým digitálním dokumentem pracovat.

Pracovat svým způsobem může i s analogovým (listinným) dokumentem, a to jeho naskenováním a převodem OCR, ale to zdaleka není tak pohodlné, především to však není stoprocentní. Více v kapitole *Jak má správně vypadat analogová verze dokumentu, aby šla zpracovat asistivní technologií*. Protože ale veřejnoprávní původci musejí povinně vytvářet výhradně digitální dokumenty, takováto situace defacto vůbec nemůže nastat. Ale velice podobné to může být s naskenovaným PDF dokumentem. Taková situace u vlastních dokumentů původce ale také nesmí nastat, neboť by tím byl porušen zákon ve formě vyhotovení druhu a formátu dokumentu.

Dokument musí splňovat základní *Technické charakteristiky a vlastnosti přístupného dokumentu*, aby byl pro každého uživatele a každý systém zcela přístupný. U dokumentů veřejné správy je to o to důležitější, že v takových dokumentech jsou pro uživatele mnohdy zcela zásadní informace a určují a mění jeho práva a povinnosti. I proto je přístupnost nezbytností. Navíc, oběma stranám to ušetří spoustu času a nervů, také úředník může těžit z textové reprezentace dokumentu při své běžné práci i při úkonech, které v elektronickém systému spisové služby nedělá tak často (kupříkladu hledání v rozsáhlé databázi dokumentů).

Uživatelé se zdravotním postižením velice často a rádi využívají digitalizaci a digitální komunikaci s úřadem, ostatně eGovernment má jako jeden z důvodů také rovnost a přístupnost, neboť v digitální formě je vše daleko přístupnější, než v listinné. K takovému uživateli se dokumenty dostanou buď prostřednictvím jeho datové schránky (je-li příjemcem), nebo si je najde na internetových stránkách a nově i v elektronických aplikacích či na portálu po přihlášení. Dokument si buď stáhne do zařízení, nebo si jej rovnou zobrazí. Dnes je PDF prohlížeč s integrovaným odečítačem (podporou pro asistivní technologie) součástí i každého webového prohlížeče, ale existují i specializované programy pro práci s PDF, jako je Acrobat Reader, nebo třeba i Microsoft Word, (ve kterém se dá PDF také otevřít).

### 2.2.2. Technické charakteristiky a vlastnosti přístupného dokumentu

Jaké vlastnosti po technické stránce tedy musí dokument mít, aby byl pro uživatele s asistivní technologií přístupný? Níže jsou specifikovány hlavní charakteristiky přístupného dokumentu.

(Překlad z <https://www.adobe.com/accessibility/pdf/pdf-accessibility-overview.html>)

Zpřístupněná PDF obsahují mimo jiné následující charakteristiky, respektive, technické náležitosti:

#### 2.2.2.1. Textová reprezentace

V rámci každého dokumentu se používá logický strom značených struktur, který poskytuje smysluplné pořadí čtení obsahu a také metodu pro definování role strukturálních prvků a vztahu k obsahu stránky. V rámci této struktury značek lze poskytnout další vlastnosti, jako je alternativní text a náhradní text.

#### 2.2.2.2. Vyhledatelný text

Dokument, který se skládá z naskenovaných obrázků textu, je ze své podstaty nepřístupný, protože obsah dokumentu je grafika představující písmena na stránce, nikoliv text, který lze prohledávat. Software asistenční technologie neumí číst nebo extrahovat slova v grafické reprezentaci. Uživatelé navíc nemohou vybrat nebo upravit text nebo manipulovat s PDF kvůli přístupnosti. Naskenované obrázky textu musí být převedeny na text, který lze prohledávat pomocí optického rozpoznávání znaků (OCR) před tím, než bude řešena přístupnost v dokumentu.

#### 2.2.2.3. Značky struktury dokumentu a správné pořadí čtení

Pro čtení textu dokumentu a jeho prezentaci způsobem, který dává uživateli smysl, vyžaduje čtečka obrazovky nebo jiný nástroj pro převod textu na řeč, aby byl dokument strukturován. Značky struktury dokumentu v PDF definují pořadí čtení a identifikují nadpisy, odstavce, sekce, tabulky a další prvky stránky. Struktura značek také umožňuje změnu velikosti a opětovné rozložení dokumentů pro prohlížení ve větších velikostech a na mobilních zařízeních.

#### 2.2.2.4. Alternativní textové popisy pro netextové prvky

Funkcím dokumentu, jako jsou obrázky a interaktivní pole formulářů, nemůže uživatel čtečky obrazovky porozumět, pokud nemají přidružený alternativní text. Přestože je text odkazu k dispozici uživatelům čtečky obrazovky, je možné poskytnout smysluplnější popisy prostřednictvím náhradního (aktuálního) textu. Alternativní text pro obrázky a nástrojové tipy může pomoci mnoha uživatelům, a to včetně těch, kteří mají poruchy učení. Musí být také přítomny ekvivalenty pro multimédia, a to včetně jakýchkoliv audio a video prvků.

#### 2.2.2.5. Písma, která umožňují extrahovat znaky do textu

Písma v přístupném PDF musí obsahovat dostatek informací, aby Acrobat mohl správně extrahovat všechny znaky do textu pro jiné účely, než je zobrazování textu na obrazovce. Acrobat extrahuje znaky do textu Unicode, když čtete PDF pomocí čtečky obrazovky nebo nástroje Read Out Loud, nebo když ukládáte jako text pro Braillovu embosovačku. Tato extrakce se nezdaří, pokud Acrobat nemůže určit, jak mapovat písmo na znaky Unicode.

#### 2.2.2.6. Interaktivní pole s popisky formulářů s přístupnými chybovými zprávami a bez načasování

Některá PDF obsahují interaktivní formuláře, které lidé vyplňují pomocí počítače. Aby byla přístupná, musí být pole formuláře interaktivní; to znamená, že uživatel musí mít možnost zadávat hodnoty do polí formuláře. Interaktivní formuláře PDF mají také definované pořadí tabulátorů, které umožňuje uživatelům asistenční technologie používat klávesu Tabulátor, aby logicky postupovali od jednoho pole formuláře nebo interaktivního ovládacího prvku k dalšímu. Úplné podrobnosti naleznete v dokumentu Adobe® Acrobat® Pro DC Accessibility Guide: Creating Accessible Forms. Formuláře musí poskytovat identifikaci, dávat tipy na správné vyplnění a předcházet chybám. Zadání formuláře by nemělo být časováno, pokud uživatel nemůže požadovat více času.

#### 2.2.2.7. Další interaktivní funkce: Hypertextové odkazy a navigační pomůcky

Navigační pomůcky v PDF -- jako jsou odkazy, záložky, nadpisy, obsah a přednastavené pořadí tabulek pro pole formuláře -- pomáhají všem uživatelům používat dokument, aniž by museli číst celý dokument slovo od slova. Obzvláště užitečné jsou záložky, které lze vytvořit z nadpisů dokumentů. K těmto funkcím lze přistupovat pomocí klávesnice bez spoléhání na myš a umožňují uživatelům více cest k obsahu navigace.

#### 2.2.2.8. Jazyk dokumentu a jednoznačný název

Určení jazyka dokumentu v PDF umožňuje některým čtečkám obrazovky přepnout aktuální syntezátor řeči do příslušného jazyka, což umožňuje správnou výslovnost obsahu v různých jazycích. Poskytnutí nadpisu dokumentu umožňuje uživateli vyhledat a identifikovat dokument.

#### 2.2.2.9. Zabezpečení, které nebude zasahovat do přístupnosti

Někteří autoři PDF omezují uživatelům tisk, kopírování, extrahování, úpravy nebo přidávání komentářů k textu. Text přístupného PDF musí být k dispozici čtečce obrazovky. Nastavení zabezpečení Acrobatu lze nastavit tak, aby chránilo obsah dokumentu a zároveň nenarušovalo schopnost čtečky obrazovky převést text na obrazovce na řeč nebo Braillovo písmo.

#### 2.2.2.10. Ostatní charakteristiky a funkce zpřístupnění dokumentu

Existují další charakteristiky přístupných dokumentů včetně:

- Nespoléhat se pouze na barvu nebo zrakové charakteristiky pro zprostředkování významu
- Použití barevných kombinací, které poskytují dostatečný stupeň kontrastu
- Ovládání zvuku
- Použití textu místo obrázků textu
- Žádné použití blikajících prvků
- Žádné změny zaměření bez iniciace uživatelem
- Konzistentní navigace a identifikace prvků

## 2.3. Přístupnost dokumentů v kontextu spisové služby a správy dokumentů

Instituce veřejného sektoru se souhrnně nazývají takzvanými veřejnoprávními původci. To jsou organizace a instituce, nejen úřady, které mají za povinnost tzv. výkon spisové služby. Stručně řečeno, spisová služba je vše, co se týká správy dokumentů, a to zejména u digitálních dokumentů. Tedy i přístupnost textového obsahu dokumentů je součástí této spisové služby. Proto je přístupnost dokumentů jednou z povinností výkonu spisové služby.

### 2.3.1. Spisová služba jako odborná správa dokumentů

Legislativa definuje takzvané veřejnoprávní původce, což jsou organizace a subjekty, které podle příslušného zákona mají za povinnost vykonávat odbornou správu dokumentů. Tu realizují výkonem spisové služby, a to zejména spisové služby v elektronické podobě.

Spisová služba je souborem procesů, a to zejména: příjem, označování, evidence, rozdělování, vyřizování, tvorba, vyhotovování, podepisování, odesílání, uzavírání, uchovávání a skartace dokumentů.

Přístupnost dokumentů je ve skutečnosti jednou z technických podrobností výkonu spisové služby, a to zejména u dokumentů vzniklých z vlastní činnosti. Každý veřejnoprávní původce má za povinnost plnit veškeré požadavky výkonu spisové služby a mezi tyto požadavky patří také vytvářet výhradně přístupné dokumenty v digitální podobě.

### 2.3.2. Druhy a formy dokumentů a jejich správy

Podle formy dokumentů rozlišujeme dokumenty na:

- Analogové (fyzické/listinné)
- Digitální (elektronické)

Podle původu pak rozlišujeme dokumenty na:

- Doručené dokumenty (od někoho jiného)
- Dokumenty vzniklé z vlastní činnosti - vlastní dokumenty (veškeré moje)

Rozlišujeme pak obsahově/technickou formu, a to na:

- Statické textové dokumenty (dokumenty, dopisy, rozhodnutí, vyhlášky)
- Statické obrazové dokumenty (fotografie, nákresy, mapy)
- Dynamické obrazové dokumenty (video, dynamické obrazové prezentace)
- Zvukové dokumenty (záznamy zvuku, hudba)
- Databáze a datové věty (XML data)

### 2.3.3. Způsoby vzniku vlastního dokumentu

Dokument v úřadu může vzniknout více různými způsoby. Přestože musejí být vždy dodrženy veškeré povinnosti a procesy správy dokumentů, technických forem vzniku a generování souboru dokumentu je více. Podle jednotlivých způsobů vzniku či získání dokumentu pro jeho odeslání nebo publikaci platí pochopitelně i rozdílné technické postupy.

Můžeme se zabývat těmito základními způsoby vzniku vlastního dokumentu:

- Výstup z elektronického systému spisové služby (ESSL): I přes to, že to úřady často ignorují, jde o jedinou správnou formu vzniku jakéhokoliv dokumentu v úřadu. ESSL je systém, v němž dochází k vyhotovování a finalizaci a odesílání dokumentu. Dokument se vždy vytváří jako digitální dokument se všemi náležitostmi.
- Výstup generovaný z jiného informačního systému (AIS/ISSD): I zde se jedná o automatické generování a tvorbu souboru dokumentu informačním systémem. Dokument v tomto případě negeneruje samotný elektronický systém spisové služby, ale jiný informační systém. Při takovém generování je nutno ale použít správnou knihovnu pro generování PDF a dodržet veškeré technické náležitosti pro dokument.
- Dokument doplňovaný ze šablony v rámci informačního systému: Informační systém nemusí generovat dokument samostatně. V řadě případů uživatel v příslušném systému připraví určité části obsahu a systém je pak doplní do předpřipravené šablony a z ní pak technicky vygeneruje PDF dokument k jeho vyhotovení a finalizaci. I zde je nezbytné dodržet veškeré technické požadavky na výsledné PDF soubory.
- Ručně vytvářený dokument mimo informační systém (na počítači úředníka): V některých případech může dokument technicky vznikat i zcela mimo elektronický systém spisové služby (a musí být pak do ESSL řádně vložen a v něm spravován), a to třeba v textovém editoru nebo v jiné aplikaci na počítači zaměstnance úřadu. I v tomto případě je nutno zajistit jeho správný výstupní formát se všemi technickými náležitostmi.
- Dokument přijatý jako doručený a poskytnutý jako odeslaný: Původce odesílá/zveřejňuje i dokumenty jiných původců (kupříkladu podklady od jiného OVM či od jiného účastníka řízení). V takovém případě platí povinnosti správy dokumentu v ESSL či ISSD a pokud dokument není ve správném výstupním formátu a je od organizace, která nemá za povinnost vykonávat spisovou službu, musí původce takový dokument převést do výstupního formátu. Zde je to ale už trochu složitější.
- Dokument jiného původce zveřejněný na úřední desce: Speciální případ předchozího způsobu. Původce je mnohdy povinen zveřejnit dokument jiného původce na své úřední desce. Problém je, pokud ten, kdo takový dokument původci zaslal, nesplnil veškeré povinnosti a požadavky na takový dokument. Původce jej má správně nezveřejnit a uložit odesílateli, aby odstranil vady dokumentu a uvedl ho do souladu se zákonem. Vzhledem k tomu, že původce nemůže při zveřejnění dokumentu na úřední desce tímto dokumentem jakkoliv technicky manipulovat, je to jediný legální způsob, jak požadavky zajistit.

## 2.4. Legislativní rámec

### 2.4.1. Legislativa

Legislativní rámec pro přístupnost je vlastně dost obsáhlý, a tak si to rozdělme na několik vrstev. Na obecné úrovni platí principy rovného přístupu a nediskriminace, následují související předpisy k dokumentům a nakonec konkrétní ustanovení k technickému řešení přístupnosti dokumentů.

Obecná úroveň:

- Úmluva o právech osob se zdravotním postižením
- Nařízení EU EIDAS
- Ústava a Listina práv a svobod
- Správní řád a správně-procesní předpisy

Předpisy týkající se dokumentů a technických záležitostí:

- Zákon č. 499/2004 Sb., o archivnictví a spisové službě
- Vyhláška č. 259/2012 Sb., o podrobnostech výkonu spisové služby
- Zákon č. 297/2016 Sb., o službách vytvářejících důvěru pro elektronické transakce
- Zákon č. 12/2020 Sb., o právu na digitální služby
- Zákon č. 99/2019 Sb., o přístupnosti internetových stránek a mobilních aplikací subjektů veřejného sektoru
- Zákon č. 365/2000 Sb., o informačních systémech veřejné správy

Kromě toho jsou pro úřady závazné i následující:

- Národní standard pro elektronické systémy spisové služby
- ISO specifikace jednotlivých norem výstupních formátů dokumentů
- Informační koncepce ČR
- Národní architektonický plán
- Spisový řád vydaný každým původcem

V této metodice není prostor vysvětlovat veškeré legislativní souvislosti, je třeba znát celý rámec k elektronizaci veřejné správy, jehož je přístupnost dokumentů jen jednou malou součástí.


### 2.4.2. Závazné normy

Digitální dokumenty ve veřejné správě se musí být v souladu s určitými technickými závaznými normami a standardy. Jedná se zejména o následující:
- Na obecné technické úrovni je to pro PDF [předpis ISO 19005 (PDF/A)](https://www.pdfa.org/resource/iso-19005-pdfa/)
- Pro přístupnost dokumentu je to závazný [předpis ISO 14289-1:2014 - Document management applications — Electronic document file format enhancement for accessibility — Part 1: Use of ISO 32000-1 (PDF/UA-1)](https://www.iso.org/standard/64599.html)

## 2.5. Povinnost vytvářet přístupné dokumenty

Ukázali jsme si velmi rozsáhlý  *Legislativní rámec*, z nějž tedy plyne obecná i konkrétní technická povinnost vytvářet  přístupné dokumenty. Protože úřady toto ale ignorovaly, přikročilo se k jednoznačnému stanovení technické přístupnosti.

Vyhláška \[504/2021 Sb. Vyhláška, kterou se mění vyhlášky provádějící zákon o archivnictví a spisové službě\], přináší nově výslovnou povinnost technické přístupnosti, a to takto:

1. V § 16 odst. 3 se za větu první vkládá věta „Veřejnoprávní původce vyhotoví dokument podle věty první v podobě, v jaké vykonává spisovou službu, ledaže povaha dokumentu takové vyhotovení vylučuje.
2. V § 16 se doplňuje odstavec 5, který zní: „Pokud veřejnoprávní původce vykonává spisovou službu v elektronické podobě v elektronickém systému spisové služby, musí jím vyhotovovaný statický textový dokument v digitální podobě nebo statický kombinovaný textový a obrazový dokument v digitální podobě obsahovat strojově čitelný text (textovou vrstvu), a bylo-li příslušné schéma XML stanoveno národním standardem, také metadata ve formátu XML. Veřejnoprávní původce zajistí soulad obsahu dokumentu ve výstupním datovém formátu s obsahem strojově čitelného textu a metadat ve formátu XML. Věty první a druhá se nepoužijí v případě, je-li dokument určen pouze pro komunikaci mezi informačními systémy.".

První bod zakotvuje povinnost, aby úřad vykonávající spisovou službu elektronicky, vytvářel vždy a výhradně digitální dokumenty. Nesmí tedy primárně vytvářet dokumenty analogové. Není tím dotčeno odesílání dokumentů v listinné podobě těm příjemcům, kteří kupříkladu nemají datovou schránku. I tak se totiž povinně vytvoří dokument digitální, opatří se validačními prvky a pak se vytiskne a odešle papírově jeho stejnopis, prvopis či druhopis. Nic to ale nemění na digitální formě dokumentu. Tím se také fakticky zakazuje postup, kdy úřady dokumenty sice tvořily digitálně, ale pak si je vytiskly, nechaly si je nelegálně fyzicky podepsat svými úředníky a pak je naskenovaly do spisové služby.

Druhý bod už znamená opravdové technické řešení přístupnosti. Tedy v souladu s příslušnými ISO specifikacemi výstupních formátů pro tyto druhy dokumentů zajistit jejich textovou vrstvu v souladu s obsahem. To je ostatně povinnost týkající se obecného splnění, aby šlo o formát dle správné mezinárodní specifikace. A přidává se i povinná datová věta u typů dokumentů, kde to bude stanoveno.

Co to znamená?

- Nesmí vytvářet jiné, než digitální dokumenty (se všemi dopady a konsekvencemi)
- Dokument musí být ve formátu PDF/A2x a vyšší a musí obsahovat textovou vrstvu (ve správné ISO specifikaci)
- Nebo je dokument také v jiném formátu (podle posledního odstavce), i pak musí obsahovat textovou vrstvu
- Není přípustné OCR, tedy pokud ESSL nezaznamenal v protokolu zodpovědnost úředníka za úplný soulad textové vrstvy
- Dokument nemající textovou vrstvu nevznikl v souladu se zákonem, tedy právně nemůže existovat
- U vybraných typů dokumentů bude povinně PDF obsahovat i standardizovanou XML datovou větu se strukturovanými informacemi a obsahem

## 2.6. Práce s přístupným dokumentem a přínosy přístupnosti

Osoba se specifickými potřebami, hlavně tedy osoba nevidomá či slabozraká, využívá pro seznámení se s obsahem digitálního dokumentu speciální softwarové a hardwarové nástroje, které jsou schopny takovou informaci ekvivalentně reprodukovat. Je důležité, aby digitální dokument při svém vzniku splňoval veškeré požadavky přístupnosti. Jestliže vznikne digitální dokument podle vyžadovaných pravidel přístupnosti, je prakticky zaručeno, že dokument, tedy jeho obsah, bude přístupný pro specifické nástroje, které využívá právě osoba nevidomá nebo osoba slabozraká.

Osoba nevidomá využívá tyto specifické nástroje, díky kterým je možné se z obsahem digitálního dokumentu plně seznámit. A mezi takové nástroje řadíme:

- ScreenReader - čtečka obrazovky s hlasovým výstupem
  - Ten je schopen odečítat textové informace viditelné na obrazovce elektronického zařízení a následně tyto informace reprodukovat uživateli prostřednictvím hlasové syntézy - umělého hlasu
- Braillský řádek
  - Ten je schopen reprodukovat textové informace viditelné na obrazovce elektronického zařízení uživateli prostřednictvím reliéfního braillova písma

Aby bylo možné všechny tyto speciální nástroje využít, je nutné, aby digitální dokument vznikl v souladu s požadavky na přístupný digitální dokument. Protože nevidomý člověk využívá klasický software pro čtení či editaci digitálního textu tak, jako běžný člověk, tedy jedná se o programy jako Acrobat Reader, Microsoft Word a další, je nutné věnovat vzniku takového dokumentu maximální pozornost stran jeho přístupnosti.
Tedy, je důležité, aby byl digitální dokument vytvořen tak, aby využíval Značky struktury dokumentu, které definují pořadí čtení a identifikují nadpisy, odstavce, sekce, tabulky a další prvky stránky. Je naprosto nezbytné, aby se v dokumentu vyskytovala vždy textová vrstva a v případě, že dokument obsahuje i určitou grafiku, aby ta byla doprovázena jejím textovým popisem, alternativním textem.
Prvky jako jsou nadpisy, odstavce, ale i tabulky a další, jsou nevidomému oporou při orientaci v digitálním dokumentu a tvoří nezbytnou součást při chápání struktury a obsahu / sdělení takového dokumentu. A screenreader všechny tyto prvky identifikuje a nabízí uživateli možnost jednak jejich zaměření prostřednictvím rychlé volby, jednak umožňuje také jejich filtrování a zobrazování v tématických seznamech / skupinách.

Osoba slabozraká využívá tyto specifické nástroje, díky kterým je možné se z obsahem digitálního dokumentu plně seznámit.  A mezi takové nástroje řadíme:

- Zvětšovací software s hlasovou podporou:  : Jedná se o speciální software, který umožňuje slabozrakému uživateli si vizuální stránku digitálního dokumentu upravit tak, aby mu plně graficky vyhovovala. Tedy, díky takovému software si může uživatel naprosto individuálně nastavit barvu popředí a pozadí tak, aby tyto dva prvky byly v co největším kontrastu. A také nastavit si velikost písma či grafiky tak, aby byl schopen tyto vizuální prvky sledovat pouhým okem či za přispění běžných optických pomůcek.
- Hlasová podpor: Jedná se o doplněk zvětšovacího software, který umožňuje slabozrakému uživateli seznámit se s větším obsahem textů tak, aby slabozraký uživatel nemusel rozsáhlý text číst zrakem. Tedy, zde využívá hlasovou syntézu, která mu reprodukuje hlasem samotný text digitálního dokumentu. A napomáhá tak k určité jeho vizuální relaxaci.

Proto je nutné, aby digitální dokument v jeho původní podobě byl vytvořen dle pravidel přístupnosti, tedy, aby byla správně zvolena barva popředí a pozadí, aby byl zvolen optimální kontrast a rozvržení obsahu digitálního dokumentu a aby digitální dokument
 neobsahoval graficky i barevně náročný obsah.

## 2.7. Důsledky nesplnění přístupnosti dokumentů

Obecně již dnes platí, že

- Veřejná správa postupuje pochopitelně pouze v souladu se zákonem, z čehož v této oblasti platí:

- Dokument, který je digitální a není ve výstupním formátu, je právně neplatný a nelze dle něj postupovat
- Dokument, který je digitální a není opatřen elektronickými validačními prvky, není právně platný a nelze podle něj postupovat
- Dokument, se kterým se díky porušení zákona nemůže příjemce seznámit, je neplatný a stát se tím dopouští úmyslného porušování ústavních práv a úmyslné šikany klienta

Nezáleží přitom na tom, jestli se chyby dopustil úředník či úřad a do jaké míry mohl úřad svým technickým vybavením tuto situaci ovlivnit. Pokud totiž takový dokument vznikne, je to důsledek úmyslného porušování zákona ze strany úřadu, na což správní právo pamatuje.

Související ustanovení Správního řádu jsou kupříkladu §\` 2 odst. 1 a 3, § 4 odst. , 4,§ 7 odst. 2,,§ 77odst.1, § 80 odst. 1 nebo 3, doplňuje i § 177 odst. 1

Dávejte si tedy na nepřístupné dokumenty pozor. Nejen, že se teď bude tato povinnost více kontrolovat, ale jejím nesplněním můžete klienty, ale i sami sebe, dostat do obrovských vleklých a nepříjemných problémů.

# 3. Jak na to

Následuje praktická část s postupy a návody na splnění povinnosti. Pokud něčemu nebudete rozumět, podívejte se do předchozí části.

Obecně jde o plnění povinností. Platí, že pokud úřad řádně plní veškeré povinnosti týkající se výkonu spisové služby, problém s přístupností dokumentů nemá. Ovšem, úřady na to moc nedbají, a pokud se vůbec obtěžují plnit něco z požadavků ohledně výkonu spisové služby, je to v zásadě nedostatečné.

1. Přestanu ignorovat potřeby a povinnosti přístupnosti dokumentů, ale zahrnu to do své schopnosti správy dokumentů
2. Prověřím si, zda jsou moje dokumenty přístupné a pokud ne, zjednám nápravu
3. Budu plně akceptovat novelu z vyhlášky 504/2021 a zajistím plnění souvisejících povinností
4. Dokumenty striktně vyhotovuji/generuji v řádném ESSL splňujícím veškeré technické požadavky
5. Neporušuji zákon tím, že původně digitální dokument vytisknu a nechám jej fyzicky podepsat někým a následně dokument naskenuji
6. Nevytvářím konverzí pouze obrazová PDF nebo PDF bez textové vrstvy dle ISO specifikace výstupního formátu
7. Zkontroluji dodavatele ESSL a všech dalších systémů, v nichž vznikají moje dokumenty, zda plní povinnosti a zda generují správné dokumenty se všemi technickými náležitostmi
8. Dokumenty vyhotovuji a vypravuji vždy ve výstupním formátu, ale mám i jejich zdrojový soubor v jiném formátu a ten v případě potřeby poskytnu také
9. Kladu důraz zejména na úřední dokumenty a rozhodnutí určené příjemcům, také na dokumenty zveřejněné na internetu

## 3.1. Zahrnutí přístupnosti dokumentů do správy dokumentů a procesů

Přístupnost dokumentů je jedním z více technických aspektů pro vyhotovování dokumentů a také pro kontrolu platnosti a úplnosti doručených dokumentů. Je tedy nezbytné se zabývat také přístupností, když řešíme procesy a činnosti spojené s dokumenty.

1. U doručených dokumentů zkontrolujeme u veřejnoprávních původců, zda dokumenty splňují veškeré náležitosti a požadavky a pouze s takovými dokumenty pracujeme.
2. U vlastních dokumentů vždy vyhotovujeme dokumenty v digitální podobě, a to se splněním všech požadavků.
3. V rámci procesů kontroly a činností metodika a manažera spisové služby dbáme také na přístupnost.

## 3.2. Náležitosti dokumentů

U dokumentů ve spisové službě jsou velice důležité jejich náležitosti. Ať už se jedná o rozhodnutí, nebo o formulář či o jiný druh dokumentu. Veřejnoprávní původci jsou povinni vytvářet jen takové dokumenty, které splňují veškeré technické požadavky a obsahové a procesní náležitosti. Celá řada z nich pak také souvisí právě s přístupností dokumentu a s jeho identifikací a určením zodpovědné osoby, která taktéž zodpovídá za přístupnost a na niž se může uživatel asistivních technologií v případě problémů a nejasností obrátit.

### 3.2.1. Obsahové náležitosti

Obecné náležitosti stanovuje Vyhláška o podrobnostech výkonu spisové služby, další obsahové náležitosti pak stanovují další předpisy (třeba Správní řád apod.). Platí ale, že každý dokument vzniklý prostřednictvím činnosti veřejnoprávního původce, a to bez výjimky, musí mít určité obsahové náležitosti, které jsou právě definovány příslušným ustanovením vyhlášky. Tyto náležitosti jsou součástí dokumentu také proto, aby v případě jakýchkoliv problémů a nejasností mohl být konkrétní dokument jednoznačně identifikován, to platí i o konkrétní osobě za dokument odpovědné a také o organizaci původce.

Základní náležitosti z pohledu obsahu a identifikace dokumentu jsou:

- Označení původce
- Číslo jednací nebo Evidenční číslo ze samostatné evidence
- Číslo jednací nebo evidenční číslo doručeného dokumentu, jedná-li se o odpověď
- Jméno, příjmení a funkce fyzické osoby pověřené jeho podpisem/vyřízením
- Datum podpisu/vyřízení dokumentu
- Podpis (kvalifikovaný elektronický podpis nebo kvalifikovaná elektronická pečeť) a časové razítko (kvalifikované elektronické časové razítko k podpisu/pečetění)
- Počet listů, počet příloh/částí

### 3.2.2. Technické a procesní náležitosti dokumentu

Technické a procesní náležitosti dokumentu jsou náležitosti a postupy, které po technické stránce zaručují platnost dokumentu. Obdobně, jako u náležitostí obsahových, i zde platí, pokud některá z uvedených věcí neplatí a není splněna, dokument nevznikl v souladu se zákonem. Proto je třeba se i těmto náležitostem důkladně věnovat.

- Dokument vznikl jako digitální dokument a po celou dobu je evidován a je s ním zacházeno jako s digitálním dokumentem
- Dokument, jeho životní cyklus a každá událost s ním spojená, jsou evidovány v ESSL nebo v ISSD a je řádně veden jeho transakční protokol
- Dokument má jasný identifikátor, kterým je buď Číslo jednací, nebo Evidenční číslo ze samostatné evidence
- K dokumentu jsou řádně evidována veškerá jeho povinná metadata a veškeré subjekty, jichž se týká (zejména odesílatel nebo příjemce)
- Dokument je řádně vyhotoven a zkontrolován před odesláním
- Dokument je vždy ve správném výstupním formátu dle jeho druhu a určení, může existovat pak i v dalších formátech
- Dokument musí obsahovat textovou vrstvu, a to dle specifikace konkrétního výstupního formátu, za její soulad zodpovídá vyřizující osoba a původce
- Dokument v okamžiku vyhotovení a validace obsahuje řádné kvalifikované validační prvky (elektronický podpis, elektronické časové razítko, elektronickou pečeť) v úrovni kvalifikované
- Dokument byl odeslán (zveřejnění je formou odeslání) řádným způsobem
- Lze kdykoliv z ESSL a transakčního protokolu dohledat každou událost, a to včetně zodpovědné osoby

Ne vše si může ověřit uživatel na svém zařízení, ale vše se dá ověřit zpětně. Co se týče technických požadavků (výstupní formát, textová vrstva a datová struktura), ty pak přímo souvisejí s čitelností a přístupností a se zpracováním obsahu dokumentu.

## 3.3. Přístupnost u druhů a forem dokumentů

V této kapitole si popíšeme to v zásadě věcně nejdůležitější, tedy, jak zajistit přístupnost u jednotlivých druhů dokumentů, a to zejména podle způsobu jejich vzniku. Na tyto postupy zajištění přístupnosti je třeba vždy velice důsledně dbát.

### 3.3.1. Přístupnost pro digitální dokumenty

Jak už bylo několikrát v tomto dokumentu nastíněno, přístupnost dokumentů je technická záležitost. Za určitých okolností sice uživatel může ovlivnit míru přístupnosti dokumentů, nicméně důležitá je technická forma, zejména však aplikace, která generuje výsledný dokument do formátu PDF. Umí-li taková aplikace vytvářet přístupné a tagované dokumenty, pak je výsledek pozitivní. Pokud ale aplikace, respektive, komponenta pro generování a vytváření PDF souboru  přístupnost ignoruje, dokument ve výsledku přístupný nebude.

V každém případě tedy technickou stránku přístupnosti řeší aplikace, ve které se dokument vytváří či generuje. Níže jsou pak rozebrány podle jednotlivých forem vzniku dokumentů způsoby, jakými se obecně přístupnost textového obsahu dokumentu zajistí.

#### 3.3.1.1. Pro dokumenty generované informačními systémy

V podkapitole [Způsoby vzniku vlastního dokumentu](#zp%C5%AFsoby-vzniku-vlastn

%C3%ADho-dokumentu+) jsou v prvních bodech popsány situace, kdy dokument vzniká automaticky vygenerováním, a to v informačním systému.

Ať už dokument generuje ESSL, nebo jiný informační systém či aplikace, musí se pro vytváření PDF používat taková knihovna PDF generátoru, která umí vygenerovat skutečně správný PDF dokument. Za to je plně zodpovědný autor a dodavatel příslušného systému.

Lze  k tomu přistupovat třemi různými způsoby:

1. PDF dokumenty generuje pouze elektronický systém spisové služby, nikoliv jiný informační systém
2. Dokumenty generuje elektronický systém spisové služby a také ostatní systémy, ale tak, že pro generování dokumentu využívají službu generátoru PDF elektronického systému spisové služby
3. Dokumenty generují i ostatní informační systémy a každý má vlastní knihovnu generátoru PDF

V prvních dvou případech správný dokument, a to včetně přístupnosti, zajistí příslušná komponenta knihovny v elektronickém systému spisové služby. ESSL používá pro samotné technické vytvoření PDF dokumentu knihovnu pro generování PDF. Ta buď z připravených dat PDF sestaví, nebo existující obsah (třeba z formátu MS Word) převede do PDF. Při obou těchto postupech musí ale výsledkem být validní PDF. Při třetí variantě, kromě ESSL, mají své knihovny pro generování dokumentů také ostatní informační systémy a aplikace a tedy se musí pro každou takovou knihovnu zajistit stoprocentní funkčnost. Za knihovny generátorů PDF jsou pak zodpovědní jednotliví dodavatelé systémů. Prostřední varianta znamená, že i ostatní aplikace využívají knihovnu v rámci ESSL a tedy je jasné, že takto generované dokumenty mají stejný technický formát, jako dokumenty z ESSL.

Na co si dát u knihovny generátoru PDF pozor?

- Musí umět jednak sestavit PDF z dat a jednak provést konverzi jiného běžného formátu do PDF.
- Výstupem musí být PDF/a dle povinného výstupního formátu dokumentu.
- Výsledné PDF/a musí splňovat veškeré požadavky technické normy pro PDF/a formát a technické normy pro přístupnost PDF/a dokumentů.
- Výsledné PDF musí být přístupné, tedy splňovat [technické charakteristiky a funkce přístupných dokumentů](#technick%C3%A9-charakteristiky-a-vlastnosti-p%C5%99%C3%ADstupn%C3%A9ho-dokumentu-technick%C3%A9-charakteristiky-a-vlastnosti-p%C5%99%C3%ADstupn%C3%A9ho-dokumentu)

#### 3.3.1.2. Pro dokumenty vytvářené v editorech

Dalším obvyklým způsobem, jak se vytvářejí dokumenty, je vytvářet je přímo v nějakém textovém editoru. Do skupiny textových editorů, nebo editorů obecně, počítáme nejen textové procesory, ale například i tabulkové editory, nebo jakékoliv programy na počítači úředníka, ze kterých daný program Vytváří výstup ve formátu PDF. U editorů také platí, že v naprosté většině případů si editor vnitřně zavolá nějakou knihovnu pro vygenerování PDF dokumentů a tu používá. Výhodou v těchto případech je, že pokud nějaký editor od určitého výrobce vytváří správné soubory, máte takřka jistotu, že i ostatní programy od téhož výrobce se budou k PDF výstupu chovat obdobně.

Přesto je v případě editoru nutné myslet na jednu věc, která z podstaty odpadá u dokumentů generovaných z ESSL, nebo z nějakého jiného informačního systému. Zatímco takové informační systémy dokumenty sestavují z nějakých předpřipravených bloků a šablon, v případě dokumentu vytvořeného v textovém editoru je bohužel plně na uživateli, jak bude dokument vypadat a jak bude sestaven. Uživatel tedy musí již při vytváření myslet na to, aby nevyužíval nějaké prvky či textové formátování, které by samo o sobě nebylo dostatečně přístupné.

Na co je třeba si dávat v editoru při psaní dokumentu pozor?

- Strukturu dokumentu dělat přes styly odstavců Nadpis 1, Nadpis 2, Nadpis 3... Tedy nadpis není to, co je tučné a podtržené, nebo má větší písmo, ale musí to být opravdu technicky nadpis.
- Pokud je do dokumentu vložen obrázek, nákres, tabulka či jakýkoliv jiný objekt, než souvislý text, musí být správně označen a pojmenován a musí k němu být připojen alternativní text s jeho popisem.
- Musí se dodržovat principy pro přístupnost obsahu, tedy kontrasty barev, poměr mezi textem a pozadím, velikostí písma a podobné věci. Je vhodné vycházet z potřeb norem pro obsahy webové stránky.
- Dokument si musíme před jeho exportem do PDF zkontrolovat z hlediska přístupnosti, což většina dnes používaných editorů naštěstí umožňuje. Postup je u každého editoru jiný, ale stačí si jej nalézt v nápovědě.
- PDF soubor vždy generujeme k tomu určeným způsobem, tedy pomocí funkce Uložit jako, nebo Export, nikoliv s využitím pochybných metod, jako je virtuální tisk do PDF apod.
- Pozorně si přečteme nápovědu a informace od výrobce editoru k problematice přístupnosti, kde najdeme i řadu postupů pro daný editor.

#### 3.3.1.3. Pro dokumenty doručené od jiného původce

Tato oblast je velice kontroverzní. Je třeba si uvědomit, že všichni veřejnoprávní původci mají stejné povinnosti překonat určitý alibismus za situace, kdy si někdo jiný takové povinnosti neplní. Velice často se stává, že původci je doručen dokument od jiného veřejnoprávního původce (tedy od organizace,  jež má stran spisové služby a dokumentů stejné povinnosti, a to buď pro účely nějakého řízení, nebo dokonce jako dokument, který má daný původce za povinnost zveřejnit kupříkladu umístěním na úřední desku.

Ve skutečnosti existuje za situace, kdy je doručen nepřístupný dokument od jiného původce, totiž jediná legální cesta. A to dokument zcela ignorovat a vyrozumět odesílatele o porušení zákona a trvat na odstranění vad dokumentu a jeho opětovném doručení.

Tento postup se může sice jevit složitý a neuspokojivý, ale je to opravdu jediná legální cesta, jak postupovat. Vezměme si kupříkladu situaci, kdy nám nějaký úřad pošle ke zveřejnění na úřední desce jeho dokument, který se týká konkrétní fyzické osoby. Pokud tento dokument není přístupný a my jej zveřejníme na úřední desce, nejen, že tím sami porušujeme zákon, ale porušujeme také základní ústavní práva oné  fyzické osoby tím, že jsme jí touto formou doručili dokument, s jehož obsahem se nemůže seznámit, viz obecné kapitoly v teoretické části. A i přesto, že by se mohlo zdát, že za tuto situaci nemůžeme my, neboť nám byl doručen nepřístupný dokument od jiného původce, z pohledu práva jsme opravdu zodpovědní my.

Jak tedy konkrétně v takovém případě postupovat? Bude pravděpodobně nutné, abychom si u každého doručeného dokumentu jiného původce ověřili, zda takový dokument splňuje veškeré na něj kladené požadavky. Týká se to zejména technických požadavků, a to včetně požadavku na jeho přístupnost a včetně požadavku na jeho důvěryhodnost, tedy elektronické kvalifikované validační prvky. To mimochodem musí povinně zajistit elektronický systém spisové služby, o takovém ověření nás pak informovat a zapsat jeho výsledky do transakčního protokolu. V případě nepřístupného dokumentu se bude jednat o nesplnění povinnosti výstupního formátu.  Platí tedy, že dokument nám sice byl doručen po stránce spisové služby, ale nikoliv řádně doručen podle práva, a tak se musíme chovat. Pokud nějaké náležitosti dokument nesplňuje, pak takový dokument po právní stránce nemůže ani existovat a nemohl vzniknout a my tedy  nemáme povinnost takový dokument zveřejnit na úřední desce. Máme ale jinou povinnost, a to vyrozumět odesílatele takového dokumentu, že tímto dokumentem nesplnil zákonné náležitosti a povinnosti a vyzvat ho, aby dokument vytvořil znovu a správně a s veškerými technickými náležitostmi a poté nám jej znovu odeslal k zveřejnění na úřední desce. Pochopitelně to významně ovlivňuje lhůty souvisejících povinností, neboť nepřístupný dokument, (ale také například dokument bez kvalifikovaného elektronického podpisu či pečeti a časového razítka), nemá žádné právní účinky, a tedy se na nás nevztahuje povinnost jej zveřejnit a neběží ani lhůta pro jeho zveřejnění. Pochopitelně tohle vše musíme odesílateli velmi důrazně zmínit ve vyrozumění a nařídit mu, aby nesoulad a vady takto vytvořeného neplatného dokumentu napravil on.

Podle dalších povinností týkajících se spisové služby také o všem tommto vedeme záznamy v transakčním protokolu, tedy jsme právně i důkazně s obliga, neboť, pokud si my plníme všechny povinnosti výkonu spisové služby bezezbytku a řádně, není nepřístupný doručený dokument jiného původce naše chyba a my jsme postupovali dle práva a můžeme to kdykoliv dokázat.

#### 3.3.1.4. Možnost odeslat dokument také v jiném formátu

Vyhláška o podrobnostech výkonu spisové služby v ustanovení paragrafu týkajícího se povinných výstupních formátů umožňuje, aby byl dokument odeslán a distribuován také v jiném formátu. Je tedy povinností vždy vyhotovit a odeslat dokument ve výstupním formátu, ale v odůvodněných případech lze přiložit také ten samý dokument v jiném technickém formátu. To se hodí kupříkladu v případě, kdy součástí dokumentu je nějaká tabulka nebo formulář, jež je třeba vyplnit. Má to ale také své odůvodnění stran přístupnosti dokumentů. A pokud jsme v minulosti z nějakého závažného důvodu nemohli doručený dokument převést do výstupního formátu a zajistit mu také technologickou přístupnost, můžeme dokument rozeslat a zveřejnit také v jiném formátu, a to např. ve formátu zdrojového editovatelného souboru. Tím zajistíme přístupnost u dokumentů, neboť v jiném formátu může být dokument přístupný.

### 3.3.2. Jak má správně vypadat analogová verze dokumentu, aby šla zpracovat asistivní technologií

Co se týče analogového dokumentu, respektive, přístupnosti takového dokumentu adresovaného klientovi veřejné správy, který má určité speciální potřeby vyplývající z podstaty jeho postižení, je důležité, aby takový analogový dokument byl vytvořen podle určitých pravidel, která zajistí, že klient veřejné správy s postižením bude mít maximální možnost se s takovým dokumentem plně seznámit, a to za použití OCR software, který bude schopen dokument kvalitně rozpoznat a převést jej do elektronické formy přístupné i pro odečítače obrazovky, jež využívají primárně lidé se zrakovým postižením.

Analogový dokument musí splňovat určité standardy, které zajistí nejlepší možný výsledek procesu rozpoznání textu uvedeného v dokumentu prostřednictvím OCR programu. Podstatou OCR programu (Optical Character Recognition) je dokument prvně naskenovat/vyfotografovat a následně naskenovaný/vyfotografovaný obrázek automatizovaně rozpoznat, tedy rozpoznat text uvedený na tištěném dokumentu. Výsledek rozpoznání je pak možné exportovat do textového editoru, kde si jej klient veřejné správy může plně prostudovat, nebo je možné výsledek rozpoznání dokumentu prostřednictvím OCR software uložit do kýženého formátu, kupříkladu formátu \*.doc, \*.docx, \*.txt, \*.pdf apod.

Aby byl výsledek OCR procesu co nejlepší, je nutné dodržet tato pravidla:

- dokument vždy vytisknout (tzn. použít pro tisk kvalitní kancelářskou techniku)
- vyvarovat se používání \"lesklého\" papíru pro tisk dokumentu, tedy křídového papíru či foto papíru (OCR proces bude vykazovat velmi špatný výsledek rozpoznání tehdy, kdy se použije \"lesklý\" papír, jelikož světlo snímací techniky se odráží zpět a narušuje tak proces rozpoznávání)
- pro tisk dokumentu používat kvalitní, nejlépe, matný bílý papír (tzn. matný bílý papír velmi napomáhá k maximálně kvalitnímu výsledku OCR procesu)
- vyvarovat se jakéhokoliv ručního zápisu textu do dokumentu (tzn. nepsat do dokumentu ručně, rukou psaný text není naprosto vhodný pro proces OCR)
- žádným způsobem do dokumentu dodatečně nezasahovat (tzn. v případě, že se v dokumentu objeví nějaká nesrovnalost, je nutné dokument upravit v jeho digitální podobě, a pak jej opětovně vytisknout)
- zajistit maximální kontrast popředí a pozadí (tzn. použít maximálně bílý papír, a naopak zvolit co nejtmavší barvu tištěného textu)
- zvolit optimální velikost tištěného textu (tzn. velikost textu zvolit tak, aby byl text dobře čitelný i pouhým okem)
- zajistit maximální čitelnost kvalifikovaných validačních prvků dokumentu (tzn. zajistit čitelnost hodnot úředního razítka a podpisu úřední osoby)
- zvolit optimální font tištěného písma (tzn. vyvarovat se používání patkového či jinak graficky náročného fontu písma)
- zvolit optimální rozvržení textu v ploše dokumentu (tzn. zajistit optimální rozprostření textu v dokumentu, a tak využít celou jeho plochu)
- analogový dokument posílat v neporušené podobě (tzn. zajistit, aby analogový dokument nebyl jakýmkoliv způsobem poničený či deformovaný)

### 3.3.3. Přístupnost u dynamických druhů dokumentů

Kromě textových a statických dokumentů, které jsou ze své podstaty vhodné pro úplné zpřístupnění obsahu, je nezbytné se věnovat také přístupnosti u ostatních druhů dokumentů. Tato metodika nemá za cíl ukázat technická řešení pro přístupnost dynamických dokumentů, přesto je nutné a vhodné pro jednotlivé dynamické druhy dokumentů dodržovat následující základní principy:

- U zvukových záznamů
  - K záznamu přidat obecný popis, co záznam obsahuje, aby si i neslyšící udělal základní představu o jeho významu
  - U záznamů, kde je to obsahově významné a vhodné, zajistit doslovný textový přepis mluveného slova
  - Mluvené slovo na záznamu namlouvat srozumitelně, a pokud záznam obsahuje zvukový podkres pod mluveným slovem, zajistit jeho hlasitost tak nízkou, aby nerušila mluvené slovo.
- U obrazového záznamu a videa
  - Platí vše, jako u zvukového záznamu, tedy pokud video obsahuje i zvukové stopy
  - Vhodný je také doslovný textový přepis, nebo dokonce překlad do znakového jazyka
  - Tam, kde je to vhodné, opatřit video zvláštní zvukovou stopou audiopopisu ve správném technickém formátu
  - Textový přepis prezentovat ve formě titulků na textovém základě v patřičném standardu pro titulky, tedy nevkládat je přímo do videostopy, ale zajistit je jako samostatný kontejner ve videu s textovým obsahem
  - Pokud jde o informativní video s jedním mluvčím, zajistit, aby byl mluvčí po celou dobu záznamu zřetelně vidět a aby zřetelně artikuloval pro případné odezírání, nebo video opatřit překladem do znakového jazyka s mluvící hlavou, aby bylo možno odezírat

## 3.4. Co je nepřípustné a co nikdy nedělat

Vyvarujte se následujícím věcem:

1. Vytváření analogových (listinných) dokumentů a jejich zpětné skenování (i s OCR). Toto jednak je v rozporu s právním řádem (viz povinnosti) a jednak se tím dokument v celém svém životním cyklu zneplatní a také mimochodem nebude přístupný.
2. Převádění digitálních dokumentů nekvalitními knihovnami, jež negenerují validní výstupní formát včetně textové vrstvy a splnění požadavků na přístupnost.

<!-- markdownlint-disable-file MD013 MD041 MD025 -->