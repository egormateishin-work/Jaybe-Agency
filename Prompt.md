PROMPT PRO CLAUDE CODE — WEBOVÁ STRÁNKA "JAYBE AGENCY" (TRAVEL AGENCY)

===========================================================
KONTEXT PROJEKTU
===========================================================
Pracujeme na školním projektu do angličtiny (CPE). Původně jsme měli dělat
prezentaci, ale nakonec jsme se rozhodli, že místo prezentace uděláme
kompletní webovou stránku. Naše (fiktivní) cestovní agentura se jmenuje
"JayBe Agency". Stránka musí být celá v angličtině, ale cílem je, aby
vypadala jako skutečný, profesionálně navržený web reálné prémiové
cestovní agentury — ne jako školní projekt a rozhodně ne jako web
poskládaný z AI šablony.

K tomuto zadání jsou přiložené 4 referenční obrázky. Ty je uvidíš přímo
(mám nahrané screenshoty), takže si je prosím pořádně prostuduj ještě
předtím, než napíšeš jakýkoli řádek kódu. Níže je jejich slovní popis,
abys věděl, na který konkrétně se v textu odkazuji, když píšu "první
obrázek", "druhý obrázek" atd.

===========================================================
POPIS PŘILOŽENÝCH REFERENČNÍCH OBRÁZKŮ
===========================================================

PRVNÍ OBRÁZEK (screenshot z Canvy, slide "OUR SERVICE"):
Snímek z prezentačního Canva šablony s fotkou zamlžených zelených hor nad
vodou na pozadí. Přes ni je položený velký tmavě modrý (navy) panel se
zaoblenými rohy, uvnitř 2x2 mřížka bílého textu: "Customized Travel
Packages", "Group Tours & Corporate Travel", "Flight and Accommodation
Booking", "Adventure and Luxury Travel", každý s krátkým popiskem pod
nadpisem. V rozích jsou bílé jednoduché liniové ikony — fotoaparát,
silueta cestovatele s kufrem, poskládaná mapa se špendlíkem.

DRUHÝ OBRÁZEK (screenshot z Canvy, slide "TRAVEL RESPONSIBLY"):
Rozdělené dvousloupcové rozvržení. Levá polovina je bílá s tmavě modrým
tučným nadpisem a odstavcem textu pod ním. Pravá polovina je tmavě modrá
(navy) s dvěma překrývajícími se fotkami (letecký pohled na auto na lesní
cestě a detail nohou/kufru cestovatele) a bílou liniovou siluetou
cestovatele s kufrem.

TŘETÍ OBRÁZEK (screenshot z Canvy, slide "ABOUT US"):
Stejné rozdělené rozvržení jako u druhého obrázku. Levá bílá polovina má
nadpis "ABOUT US" a popisný odstavec o agentuře. Pravá polovina je tmavě
modrá s fotkou palem na pláži, bílou liniovou ikonou letadla a bílou
siluetou cestovatele s kufrem.

DŮLEŽITÁ POZNÁMKA K PRVNÍM TŘEM OBRÁZKŮM: Jde o obecnou Canva šablonu
("Blue and White Simple Travel Agency Presentation"), kterou jsme si jen
prohlíželi jako inspiraci pro barevnost a styl grafiky (barvy, liniové
ikony, kompozice fotka+text). Texty a placeholder branding na těchto
slidech ("Liceria & Co.", "www.reallygreatsite.com" apod.) IGNORUJ —
nejsou to naše skutečné texty ani doména. Zajímá nás z nich pouze:
barevná paleta, styl liniových ikon, práce se siluetami a kompozice
foto/text panelů. Náš skutečný brand je "JayBe Agency".

ČTVRTÝ OBRÁZEK (screenshot z videa, koncept webu "ARCLIGHT — Orbital
Travel Desk"): Ukázka z recenzního videa o AI modelech, kde je vidět
demo webového konceptu cestovní kanceláře. Uprostřed je velký tmavý
animovaný 3D glóbus se svítícími tečkovanými kontinenty a tenkými
zářícími obloukovými čarami znázorňujícími letecké trasy mezi městy,
s malými popisky destinací (např. KEF, LHR, RAK) přímo na glóbu. Vlevo
je postranní seznam "CORRIDORS" s cenami letenek a délkou letu, vpravo
seznam "TRENDING" destinací s malými grafy vyhledávanosti. Dole je
lišta se souřadnicemi, "LIVE" indikátorem a počty uzlů/tras. V rohu je
navíc webkamera moderátora videa.

Z TOHOTO OBRÁZKU CHCEME PŘEVZÍT VÝHRADNĚ SAMOTNÝ 3D GLÓBUS — animovanou,
otáčivou zeměkouli se svítícími body destinací a obloukovými čarami
znázorňujícími lety mezi nimi, jako centrální vizuální prvek jedné
sekce webu. NECHCEME přebírat nic dalšího z tohoto obrázku: žádný
postranní seznam cen letenek, žádný seznam trendujících destinací s
grafy, žádnou spodní datovou lištu, žádné "LIVE" popisky, žádnou
webkameru ani žádný postranní text vlevo/vpravo od glóbu. Glóbus má
stát samostatně, vycentrovaný, jako čistý vizuální prvek doprovázený
maximálně krátkým nadpisem sekce.

===========================================================
BAREVNÁ PALETA
===========================================================
Vycházej přímo z barev, které vidíš na prvním až třetím obrázku:
příjemná, čitelná, spíš středně sytá modrá (rozhodně ne příliš tmavá
ani "těžká" modrá) v kombinaci s bílou, a k tomu jako doplňkový akcentní
tón tmavší navy modrá (podobná té z panelů na obrázcích), použitá
citlivě jen tam, kde dává kontrastní smysl (patička, akcentní bloky,
CTA prvky) — ne jako dominantní barva celého webu. Než začneš
implementovat, napiš nám zpátky konkrétní barevné hodnoty (hex kódy),
které jsi z obrázků odvodil a které budeš používat, ať víme, že jsme na
stejné vlně.

===========================================================
TYPOGRAFIE
===========================================================
Použij běžné, defaultní, maximálně čitelné webové písmo (systémový
font stack nebo běžné bezpatkové písmo typu Inter, ne nic exotického).
Žádné dekorativní, kaligrafické, skriptové ani jinak špatně čitelné
display fonty nikde na stránce — ani v nadpisech.

===========================================================
KROK 0 — PŘED ZAHÁJENÍM PRÁCE
===========================================================
Než napíšeš první řádek kódu, udělej toto:

1. Najdi a projdi si 5–6 nejlepších existujících webových designů pro
   cestovní agentury / travel brandy, které dokážeš dohledat jako
   inspiraci (Dribbble, Awwwards, Behance, případně reálné live weby).
   U každého si všimni, co na něm funguje dobře — rozvržení, práce se
   scrollem, hierarchie, typografie, animace — a tyto principy si
   poznamenej jako inspiraci. Nekopíruj žádný z nich 1:1, jde o to
   pochopit, jak vypadá skutečně prémiový travel design dnes.
2. Znovu se pořádně podívej na všechny 4 přiložené obrázky.
3. Až toto máš hotové, napiš nám stručný plán ještě PŘED tím, než
   začneš stavět: jaké přesné barvy použiješ, jaké písmo, seznam
   sekcí/komponent, které chceš postavit, a jak přesně se to vztahuje
   k referenčním obrázkům a nalezené inspiraci. Teprve po tomto shrnutí
   pokračuj samotnou implementací.

===========================================================
HERO SEKCE
===========================================================
Pozadí hero sekce musí zůstat prázdné/minimalistické — žádná stock
fotka, žádný gradientový "blob" v pozadí. Jediným vizuálním prvkim je
samotný animovaný text (nadpis, případně krátký podtext a CTA tlačítko).
Text musí mít maximálně propracovanou, ale vkusnou animaci — nástupní
animace při načtení stránky, jemný pohyb/parallax při scrollu, prémiové
mikrointerakce na hover stavech tlačítek a odkazů. Musí to působit
draze, moderně a profesionálně — ne jako výchozí šablona žádného
website builderu.

===========================================================
KLÍČOVÉ PRAVIDLO — ŽÁDNÁ "AI ESTETIKA"
===========================================================
Celý web, kromě hero sekce, musí být postavený z plně vlastních,
customizovaných sekcí bez jakékoli viditelné "AI stopy". Konkrétně se
VYHNI všem těmto typickým vzorcům, které dnes prozrazují weby dělané
"na jedno kliknutí" AI nástrojem:

- Žádné tabulky/karty s čísly a statistikami (typu "500+ Clients",
  "98% Satisfaction", animované počítadla čísel při scrollu)
- Žádné pulzující/blikající tečky u "live" nebo "status" indikátorů
- Žádná generická mřížka "3 ikony vedle sebe" s obecnými outline
  ikonami z běžných knihoven (Heroicons, Feather apod.) — pokud
  ikony použiješ, ať jsou vlastní, konzistentní s celkovým stylem
  (podobně jako liniové ikony na referenčních obrázcích)
- Žádné rozmazané gradientové "blob" tvary na pozadí sekcí
- Žádné generické seznamy s fajfkovými odrážkami (checkmark lists)
- Žádný "trusted by" pruh s logy firem
- Žádné bezmyšlenkovitě stejné zaoblení rohů, stíny karet a rozestupy
  na každé jednotlivé sekci — každá sekce má mít vlastní kompozici,
  ne kopii stejného "card grid" patternu
- Žádné generické karuselové "testimonials" karty s 5 hvězdičkami
- Vyhni se marketingovým klišé frázím typu "unlock the power of...",
  "seamless experience", "elevate your journey", "take it to the next
  level", "cutting-edge", "revolutionize your travel" — piš texty
  konkrétně, věcně a lidsky, ne jako obecný AI copywriting
- Vyhni se přesycení jedné konkrétní gradientové kombinaci (typicky
  fialová-do-modré), která je dnes typická pro AI generované SaaS
  landing page — drž se naší modro-bílé palety popsané výše

Místo toho ať má každá sekce vlastní, promyšlenou kompozici odpovídající
celkovému dojmu barev webu — asymetrické rozvržení tam, kde to dává
smysl, vlastní ilustrace/linkart namísto stock ikon, vlastní rytmus
mezer, a animace/přechody mezi sekcemi, které nejsou jen obyčejné
"fade-in on scroll", ale mají promyšlené časování a křivky (easing).

===========================================================
STRUKTURA STRÁNKY (ORIENTAČNĚ ~5 SEKCÍ + KONTAKT)
===========================================================
Navrhovaný tok (uprav, pokud vymyslíš lepší strukturu na základě
research z Kroku 0): Hero → O nás/příběh agentury → Naše služby →
Destinace (3D glóbus) → Proč si vybrat nás → Kontaktní formulář.
Web má být celkově dost zaměřený na téma zeměpisu/cestování — klidně
promítni tento motiv i do dalších sekcí (např. drobné mapové/geo prvky,
vizuální motivy tras, kontinentů apod.), ne jen do sekce s glóbem.
Každá sekce musí být plně vlastní design odpovídající zadané barevné
paletě, ne generická šablonová komponenta.

===========================================================
SEKCE DESTINACÍ — 3D GLÓBUS
===========================================================
Postav interaktivní, animovaný, otáčivý 3D glóbus (např. pomocí
Three.js / WebGL), inspirovaný konceptem na čtvrtém referenčním
obrázku: svítící tečkované kontinenty a animované obloukové čáry
znázorňující letecké trasy mezi několika vybranými destinacemi.
Glóbus musí stát samostatně, vycentrovaný v sekci, BEZ okolních
textových panelů, BEZ postranních seznamů cen nebo trendů — pouze
glóbus jako hlavní vizuální prvek sekce, případně doplněný krátkým
nadpisem sekce nad nebo pod ním. Glóbus by měl reagovat na interakci
uživatele (např. rotace tažením myší).

===========================================================
KONTAKTNÍ FORMULÁŘ
===========================================================
Poslední sekce webu bude animovaný, prémiově zpracovaný kontaktní
formulář (jméno, e-mail, zpráva apod.). Zatím řešíme pouze frontend/UI
a animace — backend logiku (odesílání, validace na serveru apod.)
budeme řešit až v další fázi společně, teď to není potřeba.

===========================================================
OBECNÉ POKYNY
===========================================================
Pracuj s maximální mírou soustředění, kreativity a preciznosti — cílem
je kompletní, profesionálně vypadající výstup, který bude pro uživatele
příjemný na pohled i na ovládání, plynule animovaný a bez jakýchkoliv
znaků toho, že jde o rychle poskládanou AI šablonu. Veškerý text na
webu piš v angličtině. Kvalita zpracování (UI/UX, animace, detail) má
mít absolutní prioritu před rychlostí dodání.