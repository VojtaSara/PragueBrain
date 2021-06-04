# Ročníkový projekt - Vojta Šára

# Data from maps

> Po domluvě jsem dospěl k tomu, že budu v rámci tohoto semestru "prohledávat do šířky" namísto do hloubky - tedy zkusím vytvořit co největší množství různých nápadů okolo jednoho tématu "Data from maps". Následně bych se přes letní prázdniny přepojil do druhé fáze, tedy průchodu do hloubky, kdy už s nějakou konkrétní sadou nápadů půjdu skrze implementaci a testování k nějakému funkčnímu celku. Z těchto důvodů bude následující dokument spíše dokumentovat mojí dosavadní exploraci témat - bude jakousi hromadou neotesaného kamene, ze které se až v další fázi začne vysekávat nějaký konkrétní projekt.

- Isochrones - show which points on a map are reachable within n minutes of walking / cycling / driving

![Roc%CC%8Cni%CC%81kovy%CC%81%20projekt%20-%20Vojta%20S%CC%8Ca%CC%81ra%20914ce22e26d24123be2f0488e99b1389/Untitled.png](Roc%CC%8Cni%CC%81kovy%CC%81%20projekt%20-%20Vojta%20S%CC%8Ca%CC%81ra%20914ce22e26d24123be2f0488e99b1389/Untitled.png)

Resources for isochrones:

[https://github.com/joshdoe/pysochrone](https://github.com/joshdoe/pysochrone)

[https://github.com/mapbox/osrm-isochrone](https://github.com/mapbox/osrm-isochrone)

První nápad je spojit isochrony a data o polohách kávaren (nebo jakéhokoli jiného podniku, lze stáhnout z firmy.cz) a vytvořit mapu doporučených míst pro novou kavárnu. Nebo například vybrat z databáze nemovitostí (sreality.cz) ty, které jsou dojezdově blízko určitému bodu. Z těchto důvodů bych v rámci svého projektu začal od isochron. Začnu studiem projektů, na které uvádím odkazy výše. 

- Konvoluční síť na satelitních snímcích

V návaznosti na předmět "Přírodou inspirované algoritmy" jsem natrénoval pomocí transfer learningu konvoluční neuronovou síť na jednoduchou klasifikaci satelitních snímků. V mém jednoduchém provedení žádné zásadní využití zatím nemá, ale spojením s isochrones, o kterých píšu na začátku už by například šlo ohodnotit celé město indexem blízkosti k vodě / parku / velké silnici. Dokonce mám i validaci od urbanisty, že by nástroj, který jen zabarví mapu podle toho, do jaké kategorie zástavby která část patří, by byl okamžitě využitelný v každodenní praxi.

Domnívám se, že tento přístup by mohl poskytnout další zajímavé směry explorace - stačí vymyslet, co smysluplného by šlo na mapách ještě hledat.

Ukázka fungování:

![Roc%CC%8Cni%CC%81kovy%CC%81%20projekt%20-%20Vojta%20S%CC%8Ca%CC%81ra%20914ce22e26d24123be2f0488e99b1389/results.jpg](Roc%CC%8Cni%CC%81kovy%CC%81%20projekt%20-%20Vojta%20S%CC%8Ca%CC%81ra%20914ce22e26d24123be2f0488e99b1389/results.jpg)

- Vizualizace dat

Jelikož se celý tento projekt točí okolo koncentrování dat, tak mi přijde vhodné zamýšlet se nad tím, jak tyto data následně inteligentně vizualizovat. Jeden nápad, který má podobně jako ty ostatní potenciál stát se hlavní částí celého projektu je vizualizovat data ve virtuální realitě, v nejvhodnější platformě pro nahlížení na 3D data. Pro lepší představu přikládám vizualizaci:

(tady bude brzy vizualizace)

Virtuální realita by mohla pracovat s 3D daty z Googlu, nebo například s daty z [https://app.iprpraha.cz/apl/app/model3d/](https://app.iprpraha.cz/apl/app/model3d/)

uživatel by pak mohl mapu zvětšovat / zmenšovat / pohybovat se v ní a vypínat a zapínat jednotlivé vrstvy dat. 

# Portál otevřených dat

[https://data.gov.cz/](https://data.gov.cz/)
