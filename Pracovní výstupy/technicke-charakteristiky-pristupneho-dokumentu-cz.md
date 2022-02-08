# Charakteristika zpřístupněných souborů PDF

(Překlad z https://www.adobe.com/accessibility/pdf/pdf-accessibility-overview.html)

Zpřístupněná PDF obsahují mimo jiné následující charakteristiky: respektive technické náležitosti:

## Textová reprezentace

V rámci každého dokumentu se používá logický strom značených struktur, který poskytuje smysluplné pořadí čtení obsahu a také metodu pro definování role strukturálních prvků a vztahu k obsahu stránky. V rámci této struktury značek lze poskytnout další vlastnosti, jako je alternativní text a náhradní text.

## Vyhledatelný text

Dokument, který se skládá z naskenovaných obrázků textu, je ze své podstaty nepřístupný, protože obsah dokumentu je grafika představující písmena na stránce, nikoli text, který lze prohledávat. Software asistenční technologie neumí číst nebo extrahovat slova v grafické reprezentaci. Uživatelé navíc nemohou vybrat nebo upravit text nebo manipulovat s PDF kvůli přístupnosti. Naskenované obrázky textu musí být převedeny na text, který lze prohledávat pomocí optického rozpoznávání znaků (OCR) před tím, než bude řešena přístupnost v dokumentu.

## Značky struktury dokumentu a správné pořadí čtení

Pro čtení textu dokumentu a jeho prezentaci způsobem, který dává uživateli smysl, vyžaduje čtečka obrazovky nebo jiný nástroj pro převod textu na řeč, aby byl dokument strukturován. Značky struktury dokumentu v PDF definují pořadí čtení a identifikují nadpisy, odstavce, sekce, tabulky a další prvky stránky. Struktura značek také umožňuje změnu velikosti a opětovné rozložení dokumentů pro prohlížení ve větších velikostech a na mobilních zařízeních.

## Alternativní textové popisy pro netextové prvky

Funkcím dokumentu, jako jsou obrázky a interaktivní pole formulářů, nemůže uživatel čtečky obrazovky porozumět, pokud nemají přidružený alternativní text. Přestože je text odkazu k dispozici uživatelům čtečky obrazovky, je možné poskytnout smysluplnější popisy prostřednictvím náhradního (aktuálního) textu. Alternativní text pro obrázky a nástrojové tipy může pomoci mnoha uživatelům, včetně těch, kteří mají poruchy učení. Musí být také přítomny ekvivalenty pro multimédia, včetně jakýchkoli audio a video prvků.


## Písma, která umožňují extrahovat znaky do textu

Písma v přístupném PDF musí obsahovat dostatek informací, aby Acrobat mohl správně extrahovat všechny znaky do textu pro jiné účely, než je zobrazování textu na obrazovce. Acrobat extrahuje znaky do textu Unicode, když čtete PDF pomocí čtečky obrazovky nebo nástroje Read Out Loud, nebo když ukládáte jako text pro Braillovu embosovačku. Tato extrakce se nezdaří, pokud Acrobat nemůže určit, jak mapovat písmo na znaky Unicode.

## Interaktivní pole s popisky formulářů s přístupnými chybovými zprávami a bez načasování

Některá PDF obsahují interaktivní formuláře, které lidé vyplňují pomocí počítače. Aby byla přístupná, musí být pole formuláře interaktivní; to znamená, že uživatel musí mít možnost zadávat hodnoty do polí formuláře. Interaktivní formuláře PDF mají také definované pořadí tabulátorů, které umožňuje uživatelům asistenční technologie používat klávesu Tabulátor, aby logicky postupovali od jednoho pole formuláře nebo interaktivního ovládacího prvku k dalšímu. Úplné podrobnosti naleznete v dokumentu Adobe® Acrobat® Pro DC Accessibility Guide: Creating Accessible Forms. Formuláře musí poskytovat identifikaci, dávat tipy na správné vyplnění a předcházet chybám. Zadání formuláře by nemělo být časováno, pokud uživatel nemůže požadovat více času.

## Další interaktivní funkce: Hypertextové odkazy a navigační pomůcky

Navigační pomůcky v PDF – jako jsou odkazy, záložky, nadpisy, obsah a přednastavené pořadí tabulek pro pole formuláře – pomáhají všem uživatelům používat dokument, aniž by museli číst celý dokument slovo od slova. Obzvláště užitečné jsou záložky, které lze vytvořit z nadpisů dokumentů. K těmto funkcím lze přistupovat pomocí klávesnice bez spoléhání na myš a umožňují uživatelům více cest k obsahu navigace.

## Jazyk dokumentu a jednoznačný název

Určení jazyka dokumentu v PDF umožňuje některým čtečkám obrazovky přepnout aktuální syntetizátor řeči do příslušného jazyka, což umožňuje správnou výslovnost obsahu v různých jazycích. Poskytnutí nadpisu dokumentu umožňuje uživateli vyhledat a identifikovat dokument.

## Zabezpečení, které nebude zasahovat do přístupnosti

Někteří autoři PDF omezují uživatelům tisk, kopírování, extrahování, úpravy nebo přidávání komentářů k textu. Text přístupného PDF musí být k dispozici čtečce obrazovky. Nastavení zabezpečení Acrobatu lze nastavit tak, aby chránilo obsah dokumentu a zároveň nenarušovalo schopnost čtečky obrazovky převést text na obrazovce na řeč nebo Braillovo písmo.


Ostatní charakteristiky a funkce zpřístupnění dokumentu

Existují další charakteristiky přístupných dokumentů včetně:

- Nespoléhat se pouze na barvu nebo zrakové  charakteristiky pro zprostředkování významu
- Použití barevných kombinací, které poskytují dostatečný stupeň kontrastu
- Ovládání zvuku
- Použití textu místo obrázků textu
- Žádné použití blikajících nebo blikajících prvků
- Žádné změny zaměření bez iniciace uživatelem
- Konzistentní navigace a identifikace prvků
