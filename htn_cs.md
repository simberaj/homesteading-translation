# Kolíkování noosféry

Eric Steven Raymond, 2000

## Paradox na úvod

Kdokoliv na internetu chvíli pozoruje živý a neuvěřitelně produktivní svět
otevřeného *(open-source)* softwaru, nemůže si nevšimnout zajímavého nesouladu
mezi tím, čemu open-source hackeři věří dle svého vlastního tvrzení, a tím,
jak se skutečně chovají - mezi oficiální ideologií open-source kultury a tím,
jak to vypadá v praxi.

Každá kultura se neustále mění a přizpůsobuje okolnostem. Open-source kultura
je odpovědí na určitou sadu potřeb a tlaků; a jako obvykle, to, jak se tato
kultura přizpůsobila okolnostem, se projevuje jak jako vědomá ideologie,
tak jako implicitní, více či méně zpřítomněné povědomí. A jak se často stává,
toto povědomí a ideologie jsou částečně v rozporu.

V tomto eseji se budu snažit poodhalit kořeny tohoto paradoxu a pomocí něj
pojmenovat zmíněné potřeby a tlaky, které utvářejí open-source kulturu.
Odvodím několik zajímavostí o ní a jejích zvycích a skončím u návrhů,
jak by se znalosti v ní implicitně obsažené daly lépe využít.

## Rozmanitost ideologie hackerů

Ideologie internetové open-source kultury (čemu hackeři dle vlastních slov
věří) je poměrně komplikovaná záležitost sama o sobě. Všichni její členové se
shodují, že otevřený software (tedy software, který je volně šiřitelný a
upravitelný a může se tak vyvíjet podle měnících se potřeb) je dobrá věc hodná
společného snažení. Víra v tento předpoklad je úhelným kamenem open-source
kultury, ale důvody, pro něž jednotlivci i různé subkultury tuto víru
vyznávají, se často velmi liší.

Jedním z rozdílů je míra horlivosti - jestli vývoj otevřeného softwaru
pokládají jen za zajímavý prostředek k dosažení cíle (dobré nástroje a zábavné
hračky) nebo za cíl sám o sobě.

Horlivý člověk prohlásí: "Svobodný software je můj život! Jsem na světě proto,
abych tvořil užitečné, krásné programy a zdroje informací, a pak je rozdával."
Méně horlivý řekne: "Otevřený software je dobrá věc a neváhám strávit dost času
na jeho vylepšování." Člověk bez horlivosti řekne: "Ano, otevřený software se
občas hodí. Hraju si s ním a uznávám lidi, kteří ho tvoří."

Dalším rozdílem je míra nepřátelství ke komerčnímu softwaru a společnostem,
které jsou na trhu s ním považovány za dominantní.

Člověk silně nepřátelský proti komerčnímu softwaru by mohl prohlásit: "Komerční
software je krádež a křečkování *(hoarding)*. Píšu svobodný software, abych
toto zlo odstranil." Od mírně nepřátelského bychom mohli zaslechnout: "Komerční
software jako takový je v pořádku, protože programátoři by měli dostat
zaplaceno, ale firmy, které bohatnou na odfláknutých produktech a zneužívají
svého postavení, jsou špatné." Člověk bez nepřátelství řekne: "Komerční
software je v pořádku, otevřený software používám prostě proto, že mi vyhovuje
víc." (A v poslední době - po vydání první verze tohoto eseje -, jak open
source postupně získává v branži na významu, můžeme slyšet i "Komerční software
je v pohodě, dokud k němu dostanu zdrojový kód nebo dělá to, co potřebuju.")

Každý z devíti názorů tvořených průnikem těchto dvou rozměrů lze nalézt v
open-source kultuře. Má význam se věnovat jejich rozdílům, protože jejich
zastánci sledují různé cíle, spolupracují různě a různě se přizpůsobují
novým podmínkám.

Historicky byla nejviditelnější a nejlépe organizovanou částí hackerské kultury
ta horlivá a silně nepřátelská vůči komerci. Free Software Foundation, založená
Richardem M. Stallmanem (RMS), stála od začátku osmdesátých let za velkým
množstvím otevřených softwarových projektů, včetně nástrojů jako Emacs a GCC,
které jsou stále základem internetového open-source světa a zdá se, že tomu
tak po určitou dobu zůstane.

Po mnoho let byla FSF jediným a nejdůležitejším ohniskem aktivity open-source
hackerů a vytvořila obrovské množství nástrojů, které jsou pro kulturu stále
nezbytné. FSF byla také dlouho jediným institucionalizovaným podporovatelem
otevřeného softwaru známým i mimo jeho kulturu. V podstatě určili význam
spojení "svobodný software" *(free software)* a úmyslně jej zaměřili
konfrontačně (čemuž se nové označení "otevřený software" *(open source)* zrovna
tak úmyslně vyhýbá).

Z tohoto důvodu byla vně i uvnitř open-source kultury tendence ji
identifikovat s horlivostí a antikomerčním postojem FSF. RMS sám odmítá, že by
byl proti komerci, ale jeho cíle tak chápe většina lidí, včetně mnoha jeho
nejhlasitějších příznivců. Jasná a mohutná kampaň FSF na "zastavení křečkování
softwaru" se nejvíce přiblížila k postavení ideologie hackerů a RMS k jejich
ideovému vůdci.

Licenční podmínky FSF, *General Public License* (GPL), vyjadřují postoje FSF.
V open-source světě jsou široce používané. V Metalabu (dříve Sunsite; *dnes
ibiblio, předchůdce dnešního GitHubu, pozn. překl.*), největším a
nejpopulárnějším archivu softwaru v linuxovém světě, v červenci 1997 používala
GPL zhruba polovina softwarových balíčků, které měly uvedeny licenční podmínky.
*(Tato dominance se postupně snižuje, v roce 2015 používalo některou z variant
GPL cca 20 % repozitářů na GitHubu.)*

Ale FSF nikdy nebyla jediným hráčem na scéně. V hackerské kultuře vždy
existoval i tišší, méně konfrontační a komerci otevřenější proud. Tito
pragmatici byli spíše než k ideologii příchylnější k inženýrským tradicím
z počátků otevřeného softwaru před nástupem FSF, které zahrnovaly především
propojené subkultury kolem Unixu a internetu před nástupem jeho komerčního
využití.

Postoje typického pragmatika jsou jen mírně zaměřené proti komerci a jeho
hlavní výčitkou vůči korporátnímu světu není "křečkování" samo o sobě, jako
spíše jeho perverzní odpor vůči přechodu na pokročilejší technologie kolem
Unixu, otevřených standardů a otevřeného softwaru. Jestli pragmatik někoho
nesnáší, je to -- spíše než všeobecně "křečci" -- král Kláda softwarového
establishmentu, dříve IBM, dnes Microsoft.

Pro pragmatiky je GPL důležitá jako nástroj spíše než jako cíl. Nevidí její
hlavní hodnotu jako zbraně proti křečkování, ale jako důležitý prvek
podporující sdílení softwaru a "tržišťových" (TODO ref) *(bazaar-mode)*
komunit kolem něj. Pragmatik si více cení dobrých nástrojů a hraček, než že by
odmítal komerci, a klidně bez ideologického problému použije kvalitní komerční
software. Zároveň jej ale jeho zkušenost s otevřeným softwarem naučila na
standardy kvality, které málokterý uzavřený software dokáže splnit.

Po mnoho let se pragmatický pohled na věc projevoval uvnitř hackerské kultury
hlavně jako tvrdohlavý proud odmítající kompletně přijmout GPL nebo obecně
program FSF. Po většinu osmdesátých let a začátek let devadesátých byl tento
proud často ztotožňován s fanklubem Berkeley Unixu, uživateli licence BSD a
zárodečnými pokusy postavit z BSD kódu otevřený Unix. Tyto pokusy však kolem
sebe nedokázaly postavit tržiště dostatečné velikosti, a tak se potácely
v roztříštěnosti a neefektivitě.

Pragmatismus nenašel svou základnu až do linuxové exploze kolem let 1993 a
1994. I když Linus Torvalds nikdy přímo neoponoval RMS, šel příkladem tím, že
shovívavě pohlížel na růst komerčního využití Linuxu, veřejně podporoval
používání kvalitního komerčního softwaru pro některé účely a občas lehce
zesměšňoval puristické a fanatické názory.

Vedlejším efektem rychlého růstu Linuxu byl vznik nové velké skupiny hackerů,
kteří stáli především o Linux  a FSF pro ně byla spíše historická záležitost.
I když tato nová vlna označuje Linux za "volbu generace GNU", většina z nich
napodobovala spíše Torvaldse než Stallmana.

Najednou to byli puristi bojující proti komerci, kdo se postupem času dostali
do menšiny. Jak moc se věci změnily, se ukázalo až v únoru 1998, kdy Netscape
oznámilo, že uvolní zdrojový kód Navigatoru 5.0 *(tehdejší dominantní
internetový prohlížeč a předchůdce dnešní Mozilly, pozn. překl.)* To oživilo
zájem o "svobodný software" v korporátním světě. Následná výzva hackerské
kultuře využít tuto příležitost a přeznačit výsledky svého snažení ze
"svobodného softwaru" na "otevřený software" se setkala s okamžitým souhlasem,
který všechny dotyčné překvapil.

Přirozeným vývojem se v průběhu devadesátých let i pragmatická část open-source
kultury postupně stávala polycentrickou. Z kořenů kolem Unixu a internetu
začaly rašit nové nezávislé komunity s vlastní identitou a charismatickými
vůdci. Z nich nejdůležitější po Linuxu byla subkultura kolem Perlu pod
vedením Larryho Walla. Menší, ale stále významné proudy představovaly skupiny
kolem Tcl Johna Osterhouta a Pythonu Guida van Rossuma. Všechny tři vyjádřily
svou ideologickou nezávislost tvorbou svých vlastních licenčních podmínek
odlišných od GPL. 

## Prostopášná teorie, puritánská praxe

Napříč všemi těmito změnami ale zůstávala shoda na tom, co je svobodné software
nebo otevřené software *(open-source)*. Nejvýraznější projev této shody můžeme
nalézt v open-source licencích, kterých je mnoho, ale všechny mají zásadní
společné prvky.

V roce 1997 byly tyto prvky zformovány do Debian Free Software Guidelines
a později do dokumentu Open Source Definition. Podle pravidel určených OSD
musí open-source licence chránit bezvýhradní právo kohokoliv na úpravu
otevřeného softwaru (a šíření těchto upravených verzí).

Implicitním předpokladem OSD (a OSD-kompatibilních *(dnes OSI-kompatibilních,
pozn. překl.)* licencí, např. GPL, BSD a perlovské Artistic License) je, že
*kdokoli se může hrabat v čemkoli*. Nikdo nebrání tuctu různých lidí, aby vzali
jakýkoliv open-source produkt (jako třeba gcc, kompilátor jazyka C od FSF),
zkopírovali jeho zdrojový kód, upravovali ho každý jiným směrem, ale přitom
každý ten svůj vydávali za originál.

Tomuto rozdvojení se říká fork. Nejdůležitejším znakem forku je vznik
konkurujících si projektů, které si navzájem nemohou sdílet kód, a tedy i
rozdělení komunity potenciálních vývojářů. (Existují případy, které zvenku
vypadají jako forky, ale nejsou jimi, jako třeba množení různých distribucí
Linuxu. U těchto pseudo-forků mohou existovat oddělené projekty, které ale
většinou používají společný kód a mohou navzájem těžit ze svého vývoje, takže
nejde o plýtvání silami ani technicky, ani sociologicky, a nejsou tudíž vnímány
jako fork.)

Open-source licence forky nijak neomezují, a pseudo-forky už vůbec; vlastně by
se dalo tvrdit, že obojí tiše podporují. V praxi jsou ale pseudo-forky běžné,
zatímco k forkům prakticky vůbec nedochází. Rozdvojení velkých projektů je
vzácné a téměř vždy je doprovází přejmenování a velká dávka veřejného
sebeobhajování. Na příkladech jako např. rozdělení GNU Emacs/XEmacs, gcc/egcs
nebo rozpady různých následovníků BSD je viditelné, že si zakladatelé nové
větve byli vědomi toho, že porušují vcelku zásadní pravidlo své komunity.

Ve skutečnosti (a navzdory teorii, že kdokoli se může hrabat v čemkoli) má
open-source kultura vysoce vyvinutou, ale do značné míry nevědomky přijímanou
sadu vlastnických zvyklostí. Tyto zvyklosti určují, kdo může software
upravovat, podmínky, za nichž je to možné, a především kdo má právo tyto
upravené verze distribuovat zpět komunitě.

Pravidla komunity nejlépe vyniknou, pokud se podíváme na její tabu. Bude tudíž
užitečné, když si zde některá důležitější shrneme:

- Existuje silný společenský tlak odrazující od forkování projektů. Stává se to
  jen ze zoufalé potřeby, po důkladném sebeobhájení, a nutné je nové jméno.
- Rozšiřování změn v projektu bez spolupráce s jeho moderátory se potkává s
  odsouzením vyjma speciálních případů, např. úprav umožňujících port.
- Bez výslovného souhlasu dotyčného se nikdy nemažou jména z historie projektu
  nebo seznamu přispěvatelů a udržovatelů *(maintainers)*.

Ve zbytku tohoto eseje prozkoumáme tato tabu a vlastnické zvyklosti podrobněji.
Budeme zkoumat nejen to, jak fungují, ale i co prozrazují o mezilidské dynamice
a strukturách motivace v open-source komunitě.

## Vlastnictví a open-source

Co znamená vlastnictví, pokud se dá majetek nekonečně množit, je vysoce tvárný
a okolní kultura postrádá donucovací mocenské mechanismy i tlak vzácnosti
zdrojů?

V případě open-source kultury je toto vlastně jednoduchá otázka. Vlastníkem
softwarového projektu je ten, kdo má výhradní právo, uznávané komunitou,
rozšiřovat jeho upravené verze.

(Při popisu "vlastnictví" budu nadále používat jednotné číslo, jako by všechny
projekty byly vlastněny jednotlivcem; ale mělo by být jasné, že projekty mohou
být vlastněny i skupinami. Na vnitřní dynamiku takových skupin se podíváme
později.)

Podle standardních open-source licencí jsou si všechny strany ve vývojové hře
rovny; ale v praxi existuje široce uznávaný rozdíl mezi "oficiálními"
záplatami, uznanými a integrovanými do vyvíjejícího se software veřejně
uznanými udržovateli, a "divokými" *(rogue)* záplatami od třetích stran.
Divoké záplaty jsou výjimečné a zpravidla jim málokdo věří (TODO ref RP).

Je jednoduché dokázat, že veřejné šíření je tou zásadní otázkou. Zvyklosti
vyzývají lidi, aby si software pro osobní účely upravili, pokud je to potřeba,
a nijak nebrání šířit takto upravené verze v uzavřené uživatelské nebo
vývojové skupině. Pouze pokud jsou úpravy uvolněny do celé open-source
komunity a soupeří tak s originálem, nabývá vlastnictví na významu.

Obecně existují tři způsoby, jak se dostat k vlastnictví open-source projektu.
První a nejvíce očividná je jej založit. Pokud má projekt od svého založení
pouze jednoho udržovatele a ten je stále aktivní, zvyklost vůbec nedovolí
položit otázku, kdo jej vlastní.

Druhou možností je předání od předchozího vlastníka -- tomu se někdy říká
"předání žezla" *(passing the baton)*. V komunitě se všeobecně ví, že
vlastníci projektů mají povinnost je předat kompetentním následníkům, když už
nejsou schopni nebo ochotni investovat čas do jejich vývoje nebo údržby.

Je důležité, že v případě velkých projektů se toto předání kontroly zpravidla
oznamuje s určitou mírou okázalosti. I když by bylo v open-source komunitě
neslýchané, aby okolí zasahovalo do výběru následníka, zvyklosti jasně ukazují,
že veřejná legitimita je důležitá.

U menších projektů zpravidla postačí zmínit jejich předání v přiložené historii
změn. Předpokládá se, že pokud původní vlastník ve skutečnosti nepředal projekt
dobrovolně, může znovu získat kontrolu za podpory komunity tím, že se
v rozumném čase ozve a podá námitku.

Třetím způsobem, jak získat vlastnictví projektu, je zjistit, že potřebuje
úpravy a jeho vlastník se nehlásí nebo nejeví zájem. Je zodpovědností toho,
kdo chce vlastnictví převzít, aby se nejdříve pokusil vlastníka najít. Teprve
v případě neúspěchu je možné na relevantním místě (např. v Usenet skupině
vyhrazené danému tématu) ohlásit, že projekt osiřel a že se chystá jeho
převzetí.

Zvyklost nařizuje počkat určitý čas s další zprávou oznamující změnu
vlastnictví. Pokud se někdo v tomto intervalu přihlásí, že na projektu
pracoval, jeho nárok vyhrává. Považuje se za slušné oznámit svůj záměr
vícekrát; slušnější je učinit tak na více relevantních místech (dalších mailing
listech a podobně) a ještě slušnější je určitou dobu trpělivě čekat na
odpovědi. Obecně je mandát k převzetí tím silnější, čím větší úsilí bylo
vynaloženo na kontaktování předchozího vlastníka nebo ostatních uchazečů,
pokud nedorazí pozitivní odpověď.

Pokud tento proces proběhne viditelně před zraky komunity kolem projektu a
neobjeví se žádné námitky, je možné si projekt přivlastnit a vyznačit to
v historii změn projektu. Je to ale stále méně bezpečná cesta než přímé
předání, a legitimita není v očích jeho komunity úplná, dokud nový vlastník
na vylepšení projektu neodvede podstatný kus práce.

Tyto zvyklosti jsem pozoroval posledních 20 let, od prehistorie otevřeného
softwaru před vznikem FSF. Je na nich velmi zajímavých několik věcí. Jedna
z nejzajímavějších je to, že většina hackerů je dodržovala, aniž by si to
plně uvědomovala. Tato esej může být vlastně prvním místem, kde jsou tyto
zvyklosti vcelku plně shrnuty a vědomě popsány.

Další zajímavostí je to, že tyto zvyklosti -- na to, že jsou nevědomé -- jsou
dodržovány pozoruhodně (až neuvěřitelně) spolehlivě. Pozoroval jsem vývoj
doslova stovek open-source projektů a stále mohu spočítat výrazné odchylky,
které jsem viděl nebo o nichž jsem slyšel, na prstech svých rukou.

Třetí zajímavostí je, že tyto zvyklosti se v průběhu času vyvíjely stálým
směrem -- k podpoře větší veřejné odpovědnosti a informovanosti a k větší
péči o uchování historií změn projektů a autorů těchto změn způsobem, který
(mimo jiné) podporuje legitimitu stávajících vlastníků.

Tyto zajímavé vlastnosti napovídají, že nejde o náhodně vyvinuté zvyklosti,
ale jsou výsledkem jakéhosi implicitního cíle nebo vzorce chování open-source
kultury, který tvoří úplný základ jejího chování.

Jeden z prvních čtenářů tohoto eseje poukázal na to, že v porovnání kultury
hackerů s kulturou crackerů/pirátů ("warez d00dz" uskupení kolem crackování
her a pirátských fór) velmi dobře vyniknou vzorce chování obou těchto skupin.
K d00dz se v tomto eseji ještě později pro porovnání vrátíme.