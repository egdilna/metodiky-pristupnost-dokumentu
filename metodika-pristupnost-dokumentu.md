---
author:EGdílna.cz a další přispěvatelé
category: Metodika přístupnosti dokumentů
date: datum
language: cs
title: Metodika pro přístupnost dokumentů
---



# 🖋Úvod

## Účel a použití metodiky {#účel-a-použití-metodiky}

Tento metodický dokument slouží veřejnoprávním původcům pro lepší pochopení a také jako návod na splnění povinnosti tzv. přístupnosti dokumentů. Protože jde o technickou oblast, která vyžaduje hluboké technické znalosti, ukazuje se nezbytným původcům v této oblasti pomoci.

Dokument je určen dvěma hlavním skupinám uživatelů:

-   Manažerům v organizacích původců: V tomto dokumentu se vysvětluje, co je to přístupnost dokumentů, proč ji řešit, jak pomáhá nejen osobám se zdravotním postižením a se specifickými potřebami, především však, na co nezapomenout a jak do toho. Manažer pak bude vědět, co po kom chtít, aby povinnosti byly řádně splněny.
-   Odborným a technickým pracovníkům: Tento dokument obsahuje i podrobné technické a procesní informace o přístupnosti digitálních dokumentů, o jednotlivých formátech a jejich podrobných specifikacích a o jejich řešení. Metodici a manažeři spisové služby, ale i IT pracovníci, se v něm dozvědí, co konkrétně musejí zajistit, aby jejich dokumenty v digitální podobě splňovaly veškeré technické požadavky na jejich přístupnost.

## Publikace metodiky a připomínky [[doplnitodkazy]{.smallcaps}]{.tag tag-name="doplnitodkazy"} {#publikace-metodiky-a-připomínky}

Veškeré podrobnosti, a to včetně předchozích verzí, pracovních podkladů a poznámek a také seznamu a stavu připomínek, lze nalézt v otevřeném GIT repozitáři [GitHub - egdilna/metodiky-pristupnost-dokumentu: Metodiky pro přístupnost digitálních dokumentů...](https://github.com/egdilna/metodiky-pristupnost-dokumentu)

Aktuální verze je k dispozici vždy na následujících URL adresách:

Webová verze metodiky k náhledu a čtení

-   [<https://github.com/egdilna/metodiky-pristupnost-dokumentu/blob/main/Metodika-pristupnost-dokumentu.md>](https://github.com/egdilna/metodiky-pristupnost-dokumentu/blob/main/Metodika-pristupnost-dokumentu.md)

Ke stažení v otevřeném editovatelném formátu

-   

Jakékoliv připomínky či dotazy a návrhy na změny a doplnění lze přidávat vytvořením nového Issue v repozitáři, kde lze také sledovat postup prací a již vytvořené Issues, a to [v sekci Issues v repozitáři](https://github.com/egdilna/metodiky-pristupnost-dokumentu/issues)

## HOTOVO Historie verzí

Toto je první verze metodiky z března 2022. V případě dalších verzí zde bude jejich seznam a u každé verze také popis změn.

## HOTOVO Významy některých technických pojmů

Kromě obecně používaných pojmů z oblasti spisové služby, má přístupnost dokumentů několik vlastních odborných termínů, které se v tomto dokumentu používají a u kterých musí čtenář dobře znát jejich význam:

-   Přístupnost dokumentů: Část schopnosti úřadu Správa dokumentů, která zajistí, aby každý dokument vzniklý z vlastní činnosti úřadu byl přístupný (definuje význam a potřeba pojmu)
-   Přístupný dokument: Dokument, s jehož obsahem se může seznámit kdokoliv, tedy i osoba se zdravotním postižením, a to bez nutnosti dodatečného zpracování obsahu dokumentu způsobem, k němuž nebyl dokument určen. (definuje význam a potřeba pojmu)
-   Textová reprezentace: V rámci každého dokumentu se používá logický strom značených struktur, který poskytuje smysluplné pořadí čtení obsahu a také metodu pro definování role strukturálních prvků a vztahu k obsahu stránky. V rámci této struktury značek lze poskytnout další vlastnosti, jako je alternativní text a náhradní text. (definuje překlad ISO specifikací)
-   Kontejner dokumentu: Technická část datového souboru digitálního dokumentu obsahující jednu či více komponent obsahu dokumentu, nebo komponent a jejich textových vrstev (definuje překlad ISO specifikací)
-   Textová vrstva: Reprezentace veškerého významového obsahu dokumentu formou prostého textu a jeho speciálních atributů, aby bylo možno reprezentovat jakýkoliv obsah a jeho druh a význam pouhým čtením prosté textové informace (definuje překlad ISO specifikací)
-   Tagovaný obsah: Textová vrstva obsahu dokumentu, která kromě samotného textu obsahuje i jeho speciální atributy, ze kterých je zřejmé, o jaký typ obsahu se jedná a jaký je jeho význam (definuje překlad ISO specifikací)

# 🖋Manažerské shrnutí

# 🖋Přístupnost dokumentů

## 🖋Co je přístupnost dokumentů a proč to řešit?

## Přístupný dokument a nepřístupný dokument {#přístupný-dokument-a-nepřístupný-dokument}

Je důležité co nejlépe porozumět tomu, jaký dokument je a není přístupný. Přístupné dokumenty jsou sice povinnost, ale především je to nutnost. Pro uživatele je totiž řádně čitelný jen přístupný dokument.

### Co je to vlastně přístupný dokument a jak se s ním dá pracovat {#co-je-to-vlastně-přístupný-dokument-a-jak-se-s-ním-dá-pracovat}

Přístupný dokument je digitální dokument, který je technicky vytvořen tak, že s ním a s jeho obsahem může pracovat kdokoliv, a to včetně osob se zdravotním postižením. Ti totiž potřebují pracovat s textem jeho obsahu. Dokument třeba ve formátu PDF nemusí být totiž přístupný jen proto, že je v PDF. To, co vidí běžný uživatel na obrazovce, totiž může být jen obrazová informace, nikoliv text ve strojově čitelném formátu. Představte si to tak, jako kdybyste se pokusili editovat v textovém editoru pouhý obrázek textu. Nemůžete ho upravovat, ani text z něj zkopírovat do jiného dokumentu. A přesně takto technicky funguje práce s textovým obsahem přístupného dokumentu. Uživatelé, kteří text nevidí, si jej musí nechat přečíst buď počítačovým hlasem, nebo na braillském řádku braillovým písmem. Pokud je dokument vytvořen správně, tak se s jeho obsahem může takový uživatel seznámit jako ostatní, ale kdokoliv si z textu dokumentu může i cokoliv zkopírovat či poznamenat. Zkrátka, nepracuje s obrazem viditelným na obrazovce, ale s textem jako v textovém editoru. Formát PDF/a navíc zajistí, že s obsahem dokumentu nikdo nemůže manipulovat a v textu něco změnit. Uživatel vždy věří obsahu textové vrstvy, a proto je zásadní požadavek na shodu obrazu s textem.

Jak se s přístupným dokumentem pracuje? Běžný úživatel s ním pracuje zcela klasicky jako s jakýmkoliv jiným dokumentem, nicméně může využívat výhody, jako je hledání v textu, možnost si část textu označit a zkopírovat či si dokument nechat číst nahlas umělým hlasem (to se hodí zejména u delších dokumentů a elektronických knih). Také informační systémy a aplikace mohou těžit z toho, že dokument obsahuje strojově čitelný text, a tak lze v takových dokumentech třeba i indexovat, nebo prohledávat celé složky na konkrétní text.

Uživatel s nějakým zdravotním postižením (většinou se pochopitelně jedná o nevidomé či slabozraké) používá tzv. \"Asistivní technologie\", tedy software schopný text číst umělým hlasem či zobrazit na braillském řádku. Nebo software umožňující úpravu obrazu (zvětšit a zvíraznit text, obrátit barvy, apod.). Takzvané odečítače obrazovky zprostředkovávají jakýkoliv textový obsah viditelný na obrazovce, tedy i text dokumentu. Zatímco třeba na webových stránkách či v textovém editoru to není problém, u procházení digitálního dokumentu v PDF záleží právě na tom, jestli dané PDF má textovou reprezentaci a textovou vrstvu. Bez ní se jedná jen o obrazové PDF, a to z principu čitelné není. S textovou vrstvou ale uživatel prochází text dokumentu jako na webové stránce, a to včetně případných odkazů, nadpisů, částí a popsaných obrázků. Uživatel asistivních technologií může dokumentem procházet, číst jednotlivá slova, věty či celé odstavce, rychle se přesouvat mezi částmi textu, nadpisy, odkazy, formulářovými prvky a dalším typem obsahu. Pro něj je to tak jediná cesta, jak s takovým digitálním dokumentem pracovat.

Pracovat svým způsobem může i s analogovým (listinným) dokumentem, a to jeho naskenováním a převodem OCR, ale to zdaleka není tak pohodlné, především to však není stoprocentní. Více v kapitole *Jak má správně vypadat analogová verze dokumentu, aby šla zpracovat asistivní technologií*. Protože ale veřejnoprávní původci musejí povinně vytvářet výhradně digitální dokumenty, takováto situace defacto vůbec nemůže nastat. Ale velice podobné to může být s naskenovaným PDF dokumentem. Taková situace u vlastních dokumentů původce ale také nesmí nastat, neboť by tím byl porušen zákon ve formě vyhotovení druhu a formátu dokumentu.

Dokument musí splňovat základní *Technické charakteristiky a vlastnosti přístupného dokumentu*, aby byl pro každého uživatele a každý systém zcela přístupný. U dokumentů veřejné správy je to o to důležitější, že v takových dokumentech jsou pro uživatele mnohdy zcela zásadní informace a určují a mění jeho práva a povinnosti. I proto je přístupnost nezbytností. Navíc, oběma stranám to ušetří spoustu času a nervů, také úředník může těžit z textové reprezentace dokumentu při své běžné práci i při úkonech, které v elektronickém systému spisové služby nedělá tak často (kupříkladu hledání v rozsáhlé databázi dokumentů).

Uživatelé se zdravotním postižením velice často a rádi využívají digitalizaci a digitální komunikaci s úřadem, ostatně eGovernment má jako jeden z důvodů také rovnost a přístupnost, neboť v digitální formě je vše daleko přístupnější, než v listinné. K takovému uživateli se dokumenty dostanou buď prostřednictvím jeho datové schránky (je-li příjemcem), nebo si je najde na internetových stránkách a nově i v elektronických aplikacích či na portálu po přihlášení. Dokument si buď stáhne do zařízení, nebo si jej rovnou zobrazí. Dnes je PDF prohlížeč s integrovaným odečítačem (podporou pro asistivní technologie) součástí i každého webového prohlížeče, ale existují i specializované programy pro práci s PDF, jako je Acrobat Reader, nebo třeba i Microsoft Word. (Ve kterém se dá PDF také otevřít).

### Technické charakteristiky a vlastnosti přístupného dokumentu {#technické-charakteristiky-a-vlastnosti-přístupného-dokumentu}

Jaké vlastnosti po technické stránce tedy musí dokument mít, aby byl pro uživatele s asistivní technologií přístupný? Níže jsou specifikovány hlavní charakteristiky přístupného dokumentu.

(Překlad z <https://www.adobe.com/accessibility/pdf/pdf-accessibility-overview.html>)

Zpřístupněná PDF obsahují mimo jiné následující charakteristiky, respektive, technické náležitosti:

#### Textová reprezentace {#textová-reprezentace}

V rámci každého dokumentu se používá logický strom značených struktur, který poskytuje smysluplné pořadí čtení obsahu a také metodu pro definování role strukturálních prvků a vztahu k obsahu stránky. V rámci této struktury značek lze poskytnout další vlastnosti, jako je alternativní text a náhradní text.

#### Vyhledatelný text {#vyhledatelný-text}

Dokument, který se skládá z naskenovaných obrázků textu, je ze své podstaty nepřístupný, protože obsah dokumentu je grafika představující písmena na stránce, nikoliv text, který lze prohledávat. Software asistenční technologie neumí číst nebo extrahovat slova v grafické reprezentaci. Uživatelé navíc nemohou vybrat nebo upravit text nebo manipulovat s PDF kvůli přístupnosti. Naskenované obrázky textu musí být převedeny na text, který lze prohledávat pomocí optického rozpoznávání znaků (OCR) před tím, než bude řešena přístupnost v dokumentu.

#### Značky struktury dokumentu a správné pořadí čtení {#značky-struktury-dokumentu-a-správné-pořadí-čtení}

Pro čtení textu dokumentu a jeho prezentaci způsobem, který dává uživateli smysl, vyžaduje čtečka obrazovky nebo jiný nástroj pro převod textu na řeč, aby byl dokument strukturován. Značky struktury dokumentu v PDF definují pořadí čtení a identifikují nadpisy, odstavce, sekce, tabulky a další prvky stránky. Struktura značek také umožňuje změnu velikosti a opětovné rozložení dokumentů pro prohlížení ve větších velikostech a na mobilních zařízeních.

#### Alternativní textové popisy pro netextové prvky {#alternativní-textové-popisy-pro-netextové-prvky}

Funkcím dokumentu, jako jsou obrázky a interaktivní pole formulářů, nemůže uživatel čtečky obrazovky porozumět, pokud nemají přidružený alternativní text. Přestože je text odkazu k dispozici uživatelům čtečky obrazovky, je možné poskytnout smysluplnější popisy prostřednictvím náhradního (aktuálního) textu. Alternativní text pro obrázky a nástrojové tipy může pomoci mnoha uživatelům, a to včetně těch, kteří mají poruchy učení. Musí být také přítomny ekvivalenty pro multimédia, a to včetně jakýchkoliv audio a video prvků.

#### Písma, která umožňují extrahovat znaky do textu {#písma-která-umožňují-extrahovat-znaky-do-textu}

Písma v přístupném PDF musí obsahovat dostatek informací, aby Acrobat mohl správně extrahovat všechny znaky do textu pro jiné účely, než je zobrazování textu na obrazovce. Acrobat extrahuje znaky do textu Unicode, když čtete PDF pomocí čtečky obrazovky nebo nástroje Read Out Loud, nebo když ukládáte jako text pro Braillovu embosovačku. Tato extrakce se nezdaří, pokud Acrobat nemůže určit, jak mapovat písmo na znaky Unicode.

#### Interaktivní pole s popisky formulářů s přístupnými chybovými zprávami a bez načasování {#interaktivní-pole-s-popisky-formulářů-s-přístupnými-chybovými-zprávami-a-bez-načasování}

Některá PDF obsahují interaktivní formuláře, které lidé vyplňují pomocí počítače. Aby byla přístupná, musí být pole formuláře interaktivní; to znamená, že uživatel musí mít možnost zadávat hodnoty do polí formuláře. Interaktivní formuláře PDF mají také definované pořadí tabulátorů, které umožňuje uživatelům asistenční technologie používat klávesu Tabulátor, aby logicky postupovali od jednoho pole formuláře nebo interaktivního ovládacího prvku k dalšímu. Úplné podrobnosti naleznete v dokumentu Adobe® Acrobat® Pro DC Accessibility Guide: Creating Accessible Forms. Formuláře musí poskytovat identifikaci, dávat tipy na správné vyplnění a předcházet chybám. Zadání formuláře by nemělo být časováno, pokud uživatel nemůže požadovat více času.

#### Další interaktivní funkce: Hypertextové odkazy a navigační pomůcky {#další-interaktivní-funkce-hypertextové-odkazy-a-navigační-pomůcky}

Navigační pomůcky v PDF -- jako jsou odkazy, záložky, nadpisy, obsah a přednastavené pořadí tabulek pro pole formuláře -- pomáhají všem uživatelům používat dokument, aniž by museli číst celý dokument slovo od slova. Obzvláště užitečné jsou záložky, které lze vytvořit z nadpisů dokumentů. K těmto funkcím lze přistupovat pomocí klávesnice bez spoléhání na myš a umožňují uživatelům více cest k obsahu navigace.

#### Jazyk dokumentu a jednoznačný název {#jazyk-dokumentu-a-jednoznačný-název}

Určení jazyka dokumentu v PDF umožňuje některým čtečkám obrazovky přepnout aktuální syntezátor řeči do příslušného jazyka, což umožňuje správnou výslovnost obsahu v různých jazycích. Poskytnutí nadpisu dokumentu umožňuje uživateli vyhledat a identifikovat dokument.

#### Zabezpečení, které nebude zasahovat do přístupnosti {#zabezpečení-které-nebude-zasahovat-do-přístupnosti}

Někteří autoři PDF omezují uživatelům tisk, kopírování, extrahování, úpravy nebo přidávání komentářů k textu. Text přístupného PDF musí být k dispozici čtečce obrazovky. Nastavení zabezpečení Acrobatu lze nastavit tak, aby chránilo obsah dokumentu a zároveň nenarušovalo schopnost čtečky obrazovky převést text na obrazovce na řeč nebo Braillovo písmo.

#### Ostatní charakteristiky a funkce zpřístupnění dokumentu {#ostatní-charakteristiky-a-funkce-zpřístupnění-dokumentu}

Existují další charakteristiky přístupných dokumentů včetně:

-   Nespoléhat se pouze na barvu nebo zrakové charakteristiky pro zprostředkování významu
-   Použití barevných kombinací, které poskytují dostatečný stupeň kontrastu
-   Ovládání zvuku
-   Použití textu místo obrázků textu
-   Žádné použití blikajících prvků
-   Žádné změny zaměření bez iniciace uživatelem
-   Konzistentní navigace a identifikace prvků

## Přístupnost dokumentů v kontextu spisové služby a správy dokumentů {#přístupnost-dokumentů-v-kontextu-spisové-služby-a-správy-dokumentů}

Instituce veřejného sektoru se souhrnně nazývají takzvanými veřejnoprávními původci. To jsou organizace a instituce, nejen úřady, které mají za povinnost tzv. výkon spisové služby. Stručně řečeno, spisová služba je vše, co se týká správy dokumentů, a to zejména u digitálních dokumentů. Tedy i přístupnost textového obsahu dokumentů je součástí této spisové služby. Proto je přístupnost dokumentů jednou z povinností výkonu spisové služby.

### 🖋Spisová služba jako odborná správa dokumentů

### Druhy a formy dokumentů a jejich správy {#druhy-a-formy-dokumentů-a-jejich-správy}

### Způsoby vzniku vlastního dokumentu

Dokument v úřadu může vzniknout více různými způsoby. Přestože musejí být vždy dodrženy veškeré povinnosti a procesy správy dokumentů, technických forem vzniku a generování souboru dokumentu je více. Podle jednotlivých způsobů vzniku či získání dokumentu pro jeho odeslání nebo publikaci platí pochopitelně i rozdílné technické postupy.

Můžeme se zabývat těmito základními způsoby vzniku vlastního dokumentu:

- Výstup z elektronického systému spisové služby (ESSL): I přesto, že to úřady často ignorují, jde o jedinou správnou formu vzniku jakéhokoliv dokumentu v úřadu. ESSL je systém, v němž dochází k vyhotovování a finalizaci a odesílání dokumentu. Dokument se vždy vytváří jako digitální dokument se všemi náležitostmi.
-   Výstup generovaný z jiného informačního systému (AIS/ISSD): I zde se jedná o automatické generování a tvorbu souboru dokumentu informačním systémem. Dokument v tomto případě negeneruje samotný elektronický systém spisové služby, ale jiný informační systém. Při takovém generování je nutno ale použít správnou knihovnu pro generování PDF a dodržet veškeré technické náležitosti pro dokument.
-   Dokument doplňovaný ze šablony v rámci informačního systému: Informační systém nemusí generovat dokument samostatně. V řadě případů uživatel v příslušném systému připraví určité části obsahu a systém je pak doplní do předpřipravené šablony a z ní pak technicky vygeneruje PDF dokument k jeho vyhotovení a finalizaci. I zde je nezbytné dodržet veškeré technické požadavky na výsledné PDF soubory.
-   Ručně vytvářený dokument mimo informační systém (na počítači úředníka): V některých případech může dokument technicky vznikat i zcela mimo elektronický systém spisové služby (a musí být pak do ESSL řádně vložen a v něm spravován), a to třeba v textovém editoru nebo v jiné aplikaci na počítači zaměstnance úřadu. I v tomto případě je nutno zajistit jeho správný výstupní formát se všemi technickými náležitostmi.
-   Dokument přijatý jako doručený a poskytnutý jako odeslaný: Původce odesílá/zveřejňuje i dokumenty jiných původců (kupříkladu podklady od jiného OVM či od jiného účastníka řízení). V takovém případě platí povinnosti správy dokumentu v ESSL či ISSD a pokud dokument není ve správném výstupním formátu a je od organizace, která nemá za povinnost vykonávat spisovou službu, musí původce takový dokument převést do výstupniho formátu. Zde je to ale už trochu složitější.
-   Dokument jiného původce zveřejněný na úřední desce: Speciální případ předchozího způsobu. Původce je mnohdy povinen zveřejnit dokument jiného původce na svojí úřední desce. Problém je, pokud ten, kdo takový dokument původci zaslal, nesplnil veškeré povinnosti a požadavky na takový dokument. Původce jej má správně nezveřejnit a uložit odesílateli, aby odstranil vady dokumentu a uvedl ho do souladu se zákonem. Vzhledem k tomu, že původce nemůže při zveřejnění dokumentu na úřední desce tímto dokumentem jakkoliv technicky manipulovat, je to jediný legální způsob, jak požadavky zajistit.

## KEKOREKTUŘE Legislativní rámec

Legislativní rámec pro přístupnost je vlastně dost obsáhlý a tak si to rozdělme na několik vrstev. Na obecné úrovni platí principy rovného přístupu a nediskriminace, následují související předpisy k dokumentům a nakonec konkrétní ustanovení k technickému řešení přístupnosti dokumentů.

Obecná úroveň

-   Úmluva o právech osob se zdravotním postižením
-   Nařízení EU EIDAS
-   Ústava a Listina práv a svobod
-   Správní řád a správně-procesní předpisy

Předpisy týkající se dokumentů a technických záležitostí

-   Zákon č. 499/2004 Sb., o archivnictví a spisové službě
-   Vyhláška č. 259/2012 Sb., o podrobnostech výkonu spisové služby
-   Zákon č. 297/2016 Sb., o službách vytvářejících důvěru pro elektronické transakce
-   Zákon č. 12/2020 Sb., o právu na digitální služby
-   Zákon č. 99/2019 Sb., o přístupnosti internetových stránek a mobilních aplikací subjektů veřejného sektoru
-   Zákon č. 365/2000 Sb., o informačních systémech veřejné správy

Kromě toho jsou pro úřady závazné i následující:

-   Národní standard pro elektronické systémy spisové služby
-   ISO specifikace jednotlivých norem výstupních formátů dokumentů
-   Informační koncepce ČR
-   Národní architektonický plán
-   Spisový řád vydaný každým původcem

V této metodice není prostor vysvětlovat veškeré legislativní souvislosti, je třeba znát celý rámec k elektronizaci veřejné správy, jehož je přístupnost dokumentů jen jednou malou součástí.

## KEKOREKTUŘE Povinnost vytvářet přístupné dokumenty [[aktuálněrozdělané]{.smallcaps}]{.tag tag-name="aktuálněrozdělané"} {#kekorektuře-povinnost-vytvářet-přístupné-dokumenty}

Ukázali jsme si dost obsáhlý *Legislativní rámec* nějž tedy plyne obecná i konkrétní technická povinnost dělat přístupné dokumenty. Protože úřady to ale ignorovaly, přikročilo se k jednoznačnému stanovení technické přístupnosti.

Vyhláška \[504/2021 Sb. Vyhláška, kterou se mění vyhlášky provádějící zákon o archivnictví a spisové službě\] přináší nově výslovnou povinnost technické přístupnosti, a to takto:

1.  V § 16 odst. 3 se za větu první vkládá věta „Veřejnoprávní původce vyhotoví dokument podle věty první v podobě, v jaké vykonává spisovou službu, ledaže povaha dokumentu takové vyhotovení vylučuje.
2.  V § 16 se doplňuje odstavec 5, který zní: „Pokud veřejnoprávní původce vykonává spisovou službu v elektronické podobě v elektronickém systému spisové služby, musí jím vyhotovovaný statický textový dokument v digitální podobě nebo statický kombinovaný textový a obrazový dokument v digitální podobě obsahovat strojově čitelný text (textovou vrstvu), a bylo-li příslušné schéma XML stanoveno národním standardem, také metadata ve formátu XML. Veřejnoprávní původce zajistí soulad obsahu dokumentu ve výstupním datovém formátu s obsahem strojově čitelného textu a metadat ve formátu XML. Věty první a druhá se nepoužijí v případě, je-li dokument určen pouze pro komunikaci mezi informačními systémy.".

První bod zakotvuje povinnost, aby úřad vykonávající spisovou službu elektronicky, vytvářel vždy a výhradně digitální dokumenty. Nesmí tedy primárně vytvářet dokumenty analůogové. Není tím dotčeno odesílání dokumentů v listinné podobě těm příjemcům, kteří kupŕíkladu nemají datovou schránku. I tak se totiž povinně vytvoří dokument digitání, opatří se validačními prvky a pak se vytiskne a odešle papírově jeho stejnopis, prvopis či druhopis, nic to ale nemění na digitální formě dokumentu. Tím se také fakticky zakazuje postup, kdy úřady dokumenty sice tvořily digitálně, ale pak si je vytiskly, nechaly si je nelegálně fyzicky podepsat svými úředníky a pak je naskenovaly do spisové služby.

Druhý bod už znamená opravdové technické řešení přístupnosti. Tedy v souladu s příslušnými ISO specifikacemi výstupních formát§ pro tyto druhy dokumentů zajistit jejich textovou vrstvu v souladu s obsahem. To je ostatně povinnost týkající se obecného splnění, aby šlo o formát dle správné mezinárodní specifikace. A přidává se i povinná datová věta u typů dokumentů, kde to bude stanoveno.

Co to znamená?

-   Nesmí vytvářet jiné, než digitální dokumenty (se všemi dopady a konsekvencemi)
-   Dokument musí být ve formátu PDF/A2x a vyšší a musí obsahovat textovou vrstvu (ve správné ISO specifikaci)
-   Nebo je dokument také v jiném formátu (podle posledního odstavce) a i pak musí obsahovat textovou vrstvu
-   Není přípustné OCR, pokud ESSL nezaznamenal v protokolu zodpovědnost úředníka za úplný soulad textové vrstvy
-   Dokument nemající textovou vrstvu nevznikl v souladu se zákonem, tedy právně nemůže existovat
-   U vybraných typů dokumentů bude povinně PDF obsahovat i standardizovanou XML datovou větu se strukturovanými informacemi a obsahem

## 🖋Práce s přístupným dokumentem a přínosy přístupnosti

## 🖋Důsledky nesplnění přístupnosti dokumentů

# 🖋Jak na to

## 🖋Zahrnutí přístupnosti dokumentů do správy dokumentů a procesů

## KEKOREKTUŘE Náležitosti dokumentů

U dokumentů ve spisové službě jsou velice důležité jejich náležitosti. Ať už se jedná o rozhodnutí, nebo o formulář, či o jiný druh dokumentu. Veřejnoprávní původci jsou povinni vytvářet jen takové dokumenty, které splňují veškeré technické požadavky a obsahové a procesní náležitosti. Celá řada z nich pak také souvisí právě s přístupností dokumentu a s jeho identifikací a určením zodpovědné osoby, která taktéž zodpovídá za přístupnost a na niž se může uživatel asistivních technologií v případě problémů a nejasností obrátit.

### Obsahové náležitosti {#obsahové-náležitosti}

Obecné náležitosti stanovuje Vyhláška o podrobnostech výkonu spisové služby, další obsahové náležitosti pak stanovují další předpisy (třeba Správní řád, apod.). Platí ale, že každý dokument vzniklý prostřednictvím činnosti veřejnoprávního původce, a to bez výjimky, musí mít určité obsahové náležitosti, které jsou právě definovány příslušným ustanovením vyhlášky. Tyto náležitosti jsou součástí dokumentu také proto, aby v případě jakýchkoliv problémů a nejasností mohl být konkrétní dokument jednoznačně identifikován, to platí i o konkrétní osobě za dokument odpovědné a také o organizaci původce.

Základní náležitosti z pohledu obsahu a identifikace dokumentu jsou:

-   -   Označení původce

-   Číslo jednací nebo Evidenční číslo ze samostatné evidence

-   Číslo jednací nebo evidenční číslo doručeného dokumentu, jedná-li se o odpověď

-   Jméno, příjmení a funkce fyzické osoby pověřené jeho podpisem/vyřízením

-   Datum podpisu/vyřízení dokumentu

-   Podpis (kvalifikovaný elektronický podpis nebo kvalifikovanou elektronickou pečeť) a časové razítko (kvalifikované elektronické časové razítko k podpisu/pečetění)

-   Počet listů, počet příloh/částí

### Technické a procesní náležitosti dokumentu {#technické-a-procesní-náležitosti-dokumentu}

Technické a procesní náležitosti dokumentu jsou náležitosti a postupy, které po technické stránce zaručují platnost dokumentu. Obdobně, jako u náležitostí obsahových, i zde platí, pokud některá z uvedených věcí neplatí a není splněna, dokument nevznikl v souladu se zákonem. Proto je třeba se i těmto náležitostem důkladně věnovat.

-   Dokument vznikl jako digitální dokument a po celou dobu je evidován a je s ním zacházeno jako s digitálním
-   Dokument, jeho životní cyklus a každá událost s ním spojená, jsou evidovány v ESSL nebo v ISSD a je řádně veden jeho transakční protokol
-   Dokument má jasný identifikátor, kterým je buď Číslo jednací, nebo Evidenční číslo ze samostatné evidence
-   K dokumentu jsou řádně evidována veškerá jeho povinná metadata a veškeré subjekty, jichž se týká (zejména odesílatel nebo příjemce)
-   Dokument je řádně vyhotoven a zkontrolován před odesláním
-   Dokument je vždy ve správném výstupním formátu dle jeho druhu a určení, může existovat pak i v dalších formátech
-   Dokument musí obsahovat textovou vrstvu, a to dle specifikace konkrétního výstupního formátu, za její soulad zodpovídá vyřizující osoba a původce
-   Dokument v okamžiku vyhotovení a validace obsahuje řádné kvalifikované validační prvky (elektronický podpis, elektronické časové razítko, elektronickou pečeť) v úrovni kvalifikované
-   Dokument byl odeslán (zveřejnění je formou odeslání) řádným způsobem
-   Lze kdykoliv z ESSL a transakčního protokolu dohledat každou událost, a to včetně zodpovědné osoby

Ne vše si může ověřit uživatel na svém zařízení, ale vše se dá ověřit zpětně. Co se týče technických požadavků (výstupní formát, textová vrstva a datová struktura), ty pak přímo souvisejí s čitelností a přístupností a se zpracováním obsahu dokumentu.

## 🖋Přístupnost u druhů a forem dokumentů

### 🖋Přístupnost pro digitální dokumenty

Jak už bylo několikrát v tomto dokumentu nastíněno, přístupnost dokumentů je technická záležitost. Za určitých okolností sice uživatel může ovlivnit míru přístupnosti dokumentů, nicméně důležitá je technická forma a zejména aplikace, která generuje výsledný dokument do formátu PDF. Umí-li taková aplikace vytvářet přístupné a tagované dokumenty, pak je výsledek pozitivní. Pokud ale aplikace resp. komponenta pro generování a vy tváření PDF souboru na přístupnost kašle, dokument ve výsledku přístupný nebude.

V každém případě tedy technickou stránku přístupnosti řeší aplikace, ve které se dokument Vytváří či generuje. Níže jsou pak rozebrány podle jednotlivých forem vzniku dokumentů způsoby, jakým se obecně přístupnost textového obsahu dokumentu zajistí.

#### KEKOREKTUŘE Pro dokumenty generované informačními systémy



V podkapitole [Způsoby vzniku vlastního dokumentu](#zp%C5%AFsoby-vzniku-vlastn%C3%ADho-dokumentu+) jsou v prvních bodech popsány situace, kdy dokument vzniká automaticky vygenerováním a to v informačním systému.

Ať už dokument generuje ESSL nebo jiný informační systém či aplikace, musí se pro vytváření PDF používat taková knihovna PDF generátoru, která umí vygenerovat skutečně správný PDF dokument. Za to je plně zodpovědný autor a dodavatel příslušného systému.

Dá se k tomu přistupovat třemi různými způsoby:

1. PDF dokumenty generuje pouze elektronický systém spisové služby a žádný jiný informační systém
2. Dokumenty generuje elektronický systém spisové služby a také ostatní systémy, ale tak, že pro generování dokumentu využívají službu generátoru PDF elektronického systému spisové služby
3. Dokumenty generují i ostatní informační systémy a každý má vlastní knihovnu generátoru PDF

V prvních dvou případech je za správný dokument, vćetně přístupnosti, zajistí příslušná komponenta knihovny v elektronickém systému spisové služby. ESSL používá pro samotné technické vytvoření PDF dokumentu knihovnu pro generování PDF. Ta buď z připravených dat PDF sestaví a nebo existující obsah (třeba z formátu MS Word) převede do PDF. Při obou těchto postupech musí ale výsledkem být validní PDF. Při třetí variantě kromě ESSL mají své knihovny pro generování dokumentů také ostatní informační systémy a aplikace a tedy se musí pro každou takovou knihovnu zajistit stoprocentní funkčnost. Za knihovny generátorů PDF jsou pak zodpovědní jednotliví dodavatelé systémů. Prostřední varianta znamená, že i ostatní aplikace využívají knihovnu v rámci ESSL a tedy je jasné, že takto generované dokumenty mají stejný technický formát, jako dokumenty z ESSL.

Na co si dát u knihovny generátoru PDF pozor?

- Musí umět jednak sestavit PDF z dat a jednak provést konverzi jiného běžného formátu do PDF
- Výstupem musí být PDF/a dle povinného výstupního formátu dokumentu.
- Výsledné PDF/a musí splňovat veškeré požadavky technické normy pro PDF/a formát a technické normy pro přístupnost PDF/a dokumentů.
- Výsledné PDF musí být přístupné, tedy splňovat [technické charakteristiky a funkce přístupných dokumentů](#technick%C3%A9-charakteristiky-a-vlastnosti-p%C5%99%C3%ADstupn%C3%A9ho-dokumentu-technick%C3%A9-charakteristiky-a-vlastnosti-p%C5%99%C3%ADstupn%C3%A9ho-dokumentu)

#### 🖋Pro dokumenty vytvářené v editorech

#### 🖋Pro dokumenty doručené od jiného původce

### Jak má správně vypadat analogová verze dokumentu, aby šla zpracovat asistivní technologií {#jak-má-správně-vypadat-analogová-verze-dokumentu-aby-šla-zpracovat-asistivní-technologií}

Co se týče analogového dokumentu, respektive, přístupnosti takového dokumentu adresovaného klientovi veřejné správy, který má určité speciální potřeby vyplývající z podstaty jeho postižení, je důležité, aby takový analogový dokument byl vytvořen podle určitých pravidel, která zajistí, že klient veřejné správy s postižením bude mít maximální možnost se s takovým dokumentem plně seznámit, a to za použití OCR software, který bude schopen dokument kvalitně rozpoznat a převést jej do elektronické formy přístupné i pro odečítače obrazovky, jež využívají primárně lidé se zrakovým postižením.

Analogový dokument musí splňovat určité standardy, které zajistí nejlepší možný výsledek procesu rozpoznání textu uvedeného v dokumentu prostřednictvím OCR programu. Podstatou OCR programu (Optical Character Recognition) je dokument prvně naskenovat/vyfotografovat a následně naskenovaný/vyfotografovaný obrázek automatizovaně rozpoznat, tedy rozpoznat text uvedený na tištěném dokumentu. Výsledek rozpoznání je pak možné exportovat do textového editoru, kde si jej klient veřejné správy může plně prostudovat, nebo je možné výsledek rozpoznání dokumentu prostřednictvím OCR software uložit do kýženého formátu, kupříkladu formátu \*.doc, \*.docx, \*.txt, \*.pdf apod.

Aby byl výsledek OCR procesu co nejlepší, je nutné dodržet tato pravidla:

-   dokument vždy vytisknout (tzn. použít pro tisk kvalitní kancelářskou techniku)
-   vyvarovat se používání \"lesklého\" papíru pro tisk dokumentu, tedy křídového papíru či foto papíru (OCR proces bude vykazovat velmi špatný výsledek rozpoznání tehdy, kdy se použije \"lesklý\" papír, jelikož světlo snímací techniky se odráží zpět a narušuje tak proces rozpoznávání)
-   pro tisk dokumentu používat kvalitní, nejlépe, matný bílý papír (tzn. matný bílý papír velmi napomáhá k maximálně kvalitnímu výsledku OCR procesu)
-   vyvarovat se jakéhokoliv ručního zápisu textu do dokumentu (tzn. nepsat do dokumentu ručně, rukou psaný text není naprosto vhodný pro proces OCR)
-   žádným způsobem do dokumentu dodatečně nezasahovat (tzn. v případě, že se v dokumentu objeví nějaká nesrovnalost, je nutné dokument upravit v jeho digitální podobě, a pak jej opětovně vytisknout)
-   zajistit maximální kontrast popředí a pozadí (tzn. použít maximálně bílý papír, a naopak zvolit co nejtmavší barvu tištěného textu)
-   zvolit optimální velikost tištěného textu (tzn. velikost textu zvolit tak, aby byl text dobře čitelný i pouhým okem)
-   zajistit maximální čitelnost kvalifikovaných validačních prvků dokumentu (tzn. zajistit čitelnost hodnot úředního razítka a podpisu úřední osoby)
-   zvolit optimální font tištěného písma (tzn. vyvarovat se používání patkového či jinak graficky náročného fontu písma)
-   zvolit optimální rozvržení textu v ploše dokumentu (tzn. zajistit optimální rozprostření textu v dokumentu, a tak využít celou jeho plochu)
-   analogový dokument posílat v neporušené podobě (tzn. zajistit, aby analogový dokument nebyl jakýmkoliv způsobem poničený či deformovaný)

### KEKOREKTUŘE Přístupnost u dynamických druhů dokumentů

kromě textových a statických dokumentů, které jsou ze své podstaty vhodné pro úplné zpřístupnění obsahu, je nezbytné se věnovat také přístupnosti u ostatních druhů dokumentů. Tato metodika nemá za cíl ukázat technická řešení pro přístupnost dynamických dokumentů, přesto je nutné a vhodné pro jednotlivé dynamické druhy dokumentů dodržovat následující základní principy:

-   U zvukových záznamů
    -   K záznamu přidat obecný popis, co záznam obsahuje, aby si i neslyšící udělal základní představu o jeho významu
    -   U záznamů kde je to obsahově významné a vhodné, zajistit doslovný textový přepis mluveného slova
    -   Mluvené slovo na záznamu namlouvat srozumitelně a pokud záznam obsahuje zvukový podkres pod mluveným slovem, zajistit jeho hlasitost tak nízkou, aby nerušila mluvené slovo.
-   U obrazového záznamu a videa
    -   Platí vše jako u zvukového záznamu, pokud video obsahuje i zvukové stopy
    -   Vhodný je také doslovný textový přepis, nebo dokonce překlad do znakového jazyka
    -   Tam, kde je to vhodné, opatřit video zvláštní zvukovou stopou audiopopisu ve správném technickém formátu
    -   Textový přepis prezentovat ve formě titulků na textovém základě v patřičném standardu pro titulky, tedy nevkládat je přímo do videostopy, ale zajistit je jako samostatný kontejner ve videu s textovým obsahem
    -   Pokud jde o informativní video s jedním mluvčím, zajistit, aby byl mluvčí po celou dobu záznamu zřetelně vidět a aby zřetelně artikuloval pro případné odesílání, nebo video opatřit překladem do znakového jazyka s mluvící hlavou, aby bylo možno odezírat

## 🖋Jak řešit přístupnost u jednotlivých způsobů vzniku dokumentu

## 🖋Co je nepřípustné a co nikdy nedělat

# 🖋Návodné a kontrolní seznamy
