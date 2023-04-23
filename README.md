# 💻 PROJECT: WD2 - Superhero Website

## 🥅 Overzicht en Leerdoelen

Met dit project leer je wat het verschil is tussen aanduiding en opmaak (*markup* en *style*), wat ruimte, layout, responsiveness en opmaak precies zijn en ga je de website uit WD1 voorzien van ruimte, layout en opmaak. Je gaat aan de slag met de opmaaktaal **CSS** op een gestructureerde manier.

## 🔍 Superhero Website

In het project WD1 koos je een superheld waar je een website voor uitwerkt. Je hebt je HTML voorzien van semantisch juiste elementen, zodat je alle inhoud volledig en correct weergeeft in de browser. 

Met dit project voorzie je je superheldenwebsite van opmaak. Hiervoor werken we aan de hand van de **C.U.B.E.** methode:
 - **C**omposition: alles dat met layout en ruimte te maken heeft op macro-niveau
 - **U**tilities: kleine klassen die een element van één opmaak-regel voorzien
 - **B**locks: opmaak-regels die je nog niet wist op te lossen met composition of utilities, vaak op micro-niveau
 - **E**xceptions: uitzonderingsregels op de blocks

Voordat je je website voorziet van opmaak, ga je een ontwerp zoeken of maken. Zonder ontwerp kan je niet gericht tewerk gaan. Daarna ga je elke stap van de CUBE methode één voor één doorlopen.

## 🛠️ Opdrachten

<details>
<summary>opdracht 1: website ontwerp</summary>

>  - [ ] Ga online op zoek naar een ontwerp dat jij best vindt passen bij je superheld. Ik raad je sterk aan om [één van deze templates te kiezen](https://www.w3schools.com/w3css/w3css_templates.asp).  
>       -Je kan ook zelf op zoek gaan online naar een bijpassende template, of er zelf één tekenen. Hou er rekening mee dat je de opdracht dan wel een stuk moeilijker maakt voor jezelf!
>  - [ ] Duidt de layout elementen aan op niveau 1, 2 en 3 waaruit je ontwerp bestaat.
>  - [ ] Schrijf je HTML pagina opnieuw uit. Houdt daarbij rekening met **semantiek, opdelen in grotere en kleinere delen en IDs en klassen**.
>  - [ ] Vraag aan je leerkracht om je HTML code na te kijken wanneer je hiermee klaar bent.

</details>

---

<details>
<summary>opdracht 2: Ruimte tussen macro-elementen</summary>

> **LET OP:** We maken eerst de Mobile versie van je website. Kijk je website dus ook enkel na in de Mobile Viewer van je webbrowser.
> - [ ] Maak een bestand aan genaamd `composition.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `composition.css`
> - [ ] Gebruik CSS selectors om ruimte toe te voegen tussen en in alle elementen die zich bevinden op layout niveau 1, 2 en 3.\
>       **LET OP:** Zorg ervoor dat je selectors *niet* tè specifiek zijn!
> 
> - [ ] Kijk de waardes na die je gebruikt hebt: Probeer waardes die dicht bij elkaar liggen gelijk te trekken.\
>       *bv.: heb je ergens een waarde van 31px en ergens anders een waarde van 32px, verander dan bijvoorbeeld die van 31px naar 32px.*
> - [ ] Maak voor elke veelgebruikte waarde een CSS variabele aan in het `:root` element. 
> - [ ] Vervang de waardes door het gebruik van de juiste CSS variabelen.

</details>

---

<details>
<summary>opdracht 3: Ruimte en kleur toevoegen</summary>

> **LET OP:** We maken eerst de Mobile versie van je website. Kijk je website dus ook enkel na in de Mobile Viewer van je webbrowser.
> - [ ] Maak een bestand aan genaamd `utilities.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `utilities.css`
> - [ ] Maak utility-klassen aan om ruimte tussen en in elementen toe te voegen.
>       - **LET OP:** een utility-klasse bestaat meestal uit een klasse-selector, gevolgd door *één enkele stijlregel*!
> - [ ] Voeg de utility-klassen toe in HTML waar nodig.
> - [ ] Zorg ervoor dat je utility-klassen gebruik maken van CSS variabelen.
>
> CSS variabelen maken:
> - [ ] Maak voor elke veelgebruikte kleur een CSS variabele aan in het `:root` element. 
> - [ ] Maak utility-klassen aan om kleur aan elementen toe te voegen.
>       - **LET OP:** een utility-klasse bestaat meestal uit een klasse-selector, gevolgd door *één enkele stijlregel*!
> - [ ] Voeg de utility-klassen toe in HTML waar nodig.

</details>

---

<details>
<summary>opdracht 4: Layout toevoegen</summary>

> **LET OP:** We gaan de Mobile versie van je website nu uitbreiden naar een Desktop versie. Kijk je website vanaf nu na in zowel Desktop modus als in Mobile modus.
> - [ ] Open `composition.css`
> - [ ] Voeg onderaan een media query toe voor je desktop website.
> - [ ] Voeg layout toe met behulp van CSS Grid en CSS Flexbox in de media query waar nodig, zodat je website nu ook werkt volgens je Desktop ontwerp.
> - [ ] Voeg, indien nodig, layout containers toe aan je HTML code.\
>       **LET OP:** kijk na of je Mobile ontwerp nog steeds werkt! Wanneer je layout containers toevoegt, kan het zijn dat je CSS selectors niet meer juist zijn.

</details>

---

<details>
<summary>opdracht 5: Afwerking</summary>

> **LET OP:** We gaan de Mobile versie van je website nu uitbreiden naar een Desktop versie. Kijk je website vanaf nu na in zowel Desktop modus als in Mobile modus.
> - [ ] Maak een bestand aan genaamd `blocks.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `blocks.css`
> - [ ] Pas je elementen zo aan dat ze zo goed mogelijk overeenkomen met het oorspronkelijke ontwerp.
> 
> De laatste uitzonderingen:
> - [ ] Maak een bestand aan genaamd `exceptions.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `exceptions.css`

</details>

---

## 💡 Belangrijke Termen

| Term                      | Definitie |
| ------------------------- | --------- |
| CSS                       | CSS (Cascading Style Sheets) is de taal die een HTML document opmaakt. CSS zegt hoe HTML-elementen moeten worden weergegeven in de browser.          |
| selector                  |  De selector duidt aan welke HTML elementen opmaak zullen krijgen.         |
| declaratie                | De declaratie bestaat uit 1 of meerdere opmaakregels die tussen accolades worden geplaatst.          |
| opmaak                    |   De opmaak draait rond hoe je wil dat en element er uit komt te zien. Voorbeelden hiervan zijn kleurgebruik, onderlijnen, vet, cursief,...        |
| property                  | Een opmaakregel bestaat uit een property en waarde en eindigt met een puntkomma. |
| property-value (waarde)   |  Property-value is de waarde dat je geeft aan een property. Bijvoorbeeld bij text-align kan je de waarde center meegeven waardoor de tekst wordt gecentreerd.         |
| stylesheet                |Een interne stylesheet kan worden gebruikt als één enkele HTML-pagina een unieke stijl heeft. De interne stijl wordt gedefinieerd in het style-element, in het element head.           |
| externe stylesheet        | Met een externe stylesheet kan het uiterlijk van een hele website veranderd worden door slechts één bestand te wijzigen. Een externe stylesheet is een manier om CSS code in een apart bestand te plaatsen, zodat HTML en CSS code grotendeels gescheiden blijft. Elke pagina die de stijlregels in dit bestand gebruikt moet een verwijzing naar de externe stylesheet bevatten in het link-element. Het link-element wordt geplaatst binnen in het element head.   |
| *.css                     |   De * selector wordt gebruikt om stijlregels toe te passen op alle elementen. Wil je dat alle elementen op je website een bepaald lettertype gebruiken, kan je hiervoor de * selector gebruiken.        |
| selector                  | De Selector selecteert welke HTML elementen worden aangepast door CSS. Een CSS selector kan bijvoorbeeld alle <p> elementen selecteren, zodat CSS de tekstkleur daarvan kan aanpassen.          |
| conflicterende stijlregel |   Stijlregels kunnen soms conflicteren: Wanneer je een div element van de klasse “content” hebt voorzien en een ID “koptekst” hebt gegeven, kan het wel eens gebeuren dat verschillende selectors dezelfde stijlregels proberen toe te passen. Het is daarom belangrijk om te weten welke selector voorrang krijgt.De algemene regel is: hoe specifieker de selector, hoe meer voorrang. De selectors die we tot nu toe bekeken hebben hebben hun voorrang als volgt: 1. De ID selector overschrijft alle andere stijlregels. 2. De Class selector overschrijft alle stijlregels, behalve die van de ID selector. 3. De element selector volgt na de Class selector. 4. De * selector wordt enkel aan het einde toegevoegd, als alle andere stijlregels zijn toegepast. Wanneer twee selectors even specifiek zijn geldt de onderste stijlregel in de css code.        |
| hover                     |Een hover is één van de State selectors die je moet gebruiken bij hyperlinks. De hover state zorgt ervoor dat je bijvoorbeeld het gebied waar de gebruiker met zijn muis over staat een kleur kan geven.           |
| hexadecimale kleurwaarde  |  Kleuren kunnen ook worden samengesteld met behulp van hexadecimale kleurwaarden in de vorm: #RRGGBB, waarbij RR (rood), GG (groen) en BB (blauw) hexadecimale waardes zijn tussen 00 en FF (hetzelfde als de decimale waardes 0-255). HEX-waarden zijn niet hoofdlettergevoelig: #ff0000 is hetzelfde als #FF0000.         |
| rgb kleurwaarde           |RGB-waardes worden samengesteld met behulp van deze formule: RGB (rood, groen, blauw);Elke parameter (rood, groen, blauw) bepaald de intensiteit van de kleur met een waarde tussen 0 en 255.           |
| font                      | Een ander woord voor lettertype is font. Een lettertype is de manier waarop letters, leestekens en cijfers worden weergegeven. Elke font family hoort bij één generic family. Zo is:Elke font family hoort bij één generic family. Zo is: Arial een sans-serif lettertype en Times New Roman een een serif lettertype|
| generic family            | Voorbeelden van een generic family zijn sans-serif, serif, …         |
| font family               | Voorbeelden van een font family zijn Arial, Times New Roman, …          |
| serif                     |   Dit zijn de lettertypes met kleine uiteindes aan elke letter. Font families hierin zijn: Times New Roman en Georgia.      |
| sans-serif                | Dit zijn de lettertypes zonder (sans in het frans) kleine uiteindes aan elke letter. Font families hierin zijn: Arial en Calibri.       |
| monospace                 |  Dit zijn de lettertypes waarvan elke letter exact evenveel ruimte inneemt op het scherm. Font families hierin zijn: Courier New en Roboto Mono.        |
| box model                 |  Het CSS Box Model is eigenlijk gewoon een rechthoek dat rond elk HTML element wordt geplaatst. Dit rechthoek bevat: inhoud, padding, border en margin         |
| inhoud |      De binnenkant van het rechthoek. Hierin wordt de inhoud (tekst, afbeelding, etc.) getoond van het HTML element.     |
| padding                   |    de ruimte rondom de inhoud, aan de binnenkant van de rand.       |
| border                    | De lijn die kan getekend worden rondom een HTML element. Dit is de ruimte tussen padding en margin.          |
| margin                    |    De ruimte rondom het volledige HTML element. Deze ruimte zorgt ervoor dat er ruimte is tussen dit en andere HTML elementen.        |
| width                     |     De breedte van de content van het HTML element. Standaard is de breedte van een element dus width + padding + border (+ margin).      |
| height                    |     De hoogte van de content van het HTML element. Standaard is de hoogte van een element dus height + padding + border (+ margin).      |


## 📚 Bronnen

 - https://flukeout.github.io/

---

## 🏆 Evaluatie
 
### Deadlines

 - **Week 2**: opdracht 1&2
 - **Week 4**: opdracht 3&4
 - **Week 5**: opdracht 5

### Opmaak

| A                                                                                                                                                                                     | B                                                                                                                                                                                    | C                                                                                                                                                                                                            | D                                                                                                                                                                                                                           | E                                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Selectors zijn correct en voldoende specifiek gedefinieerd. Er werd gekozen voor de correcte stijlregels met de juiste waardes en eenheden. Selectors werden samengevoegd waar nodig. | Selectors zijn correct en voldoende specifiek gedefinieerd. Er werd gekozen voor de correcte stijlregels met de juiste waardes en eenheden. Selectors worden te weinig samengevoegd. | Selectors zijn correct en voldoende specifiek gedefinieerd. Selectors worden te weinig samengevoegd. Er werd gekozen voor de correcte stijlregels, maar de waardes en eenheden werden niet correct gebruikt. | Selectors zijn correct gedefinieerd, maar zijn vaak niet specifiek genoeg. Selectors worden te weinig samengevoegd. Er werd gekozen voor de correcte stijlregels, maar de waardes en eenheden werden niet correct gebruikt. | Selectors zijn verkeerd of niet specifiek genoeg gedefinieerd. Selectors worden te weinig samengevoegd. Stijlregels, waardes en eenheden werden niet correct gebruikt. |

### Statische Websites

| A                                                                                                                                                                                                                                                                                     | B                                                                                                                                                                                                                                                     | C                                                                                                                                                                                                                                | D                                                                                                                                                                                | E                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Layout, ruimte en interactie zijn correct geïmplementeerd. De website is responsive en Mobile First ontwikkeld. Stijlregels zijn duidelijk en overzichtelijk verzameld in externe stylesheets. Je gebruikt relatieve eenheden (em, rem) en custom properties (variabelen) waar nodig. | Layout, ruimte en interactie zijn correct geïmplementeerd. De website is responsive en Mobile First ontwikkeld. Stijlregels zijn duidelijk en overzichtelijk verzameld in externe stylesheets. Je gebruikt custom properties (variabelen) waar nodig. | De interactie op jouw website is onvoldoende geïmplementeerd. Layout en ruimte zijn correct. De website is responsive en Mobile First ontwikkeld. Stijlregels zijn duidelijk en overzichtelijk verzameld in externe stylesheets. | Ruimte en interactie zijn onvoldoende geïmplementeerd. De website is onvoldoende responsive. Je layout werkt en je hebt de website ontwikkeld volgens het Mobile First principe. | Layout, ruimte en interactie zijn onvoldoende geïmplementeerd. De website is niet responsive. Er werd niet gewerkt volgens het Mobile First principe. |

### Markup

| A                                                                                                                                                                                                                                                  | B                                                                                                                                                                                                                                                                               | C                                                                                                                                                                                                                               | D                                                                                                                                                                                                                                                                                     | E                                                                                                                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Elementen worden correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn voorzien van de vereiste attributen en elk attribute is ingevuld met een correcte waarde. Bronnen zijn lokaal opgeslagen.             | Elementen worden correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn voorzien van de vereiste attributen. Attributes bevatten een foutieve waarde. Bronnen zijn lokaal opgeslagen.                                                      | Elementen worden correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn niet voorzien van de vereiste attributen. Attributes bevatten een foutieve waarde. Bronnen zijn lokaal opgeslagen. | Elementen worden niet correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn niet voorzien van de vereiste attributen. Attributes bevatten een foutieve waarde. Externe bronnen worden gebruikt, waar interne bronnen een betere oplossing zijn. | Elementen worden niet correct genest. Elementen missen de juiste openings- of sluitingstag. Attributen werden niet correct gebruikt. Er zijn te weinig elementen aanwezig om de inhoud correct over te brengen. |
| De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig en verbeteren de semantiek. Elementen zijn onderverdeeld in grotere en kleinere elementen, en er is gekozen voor een optimale oplossing. | De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig en verbeteren de semantiek. Elementen zijn onderverdeeld in grotere en kleinere elementen. Er zijn echter betere oplossingen die je had kunnen bedenken en gebruiken. | De semantisch juiste elementen werden niet altijd gebruikt. De id's en classes van elementen zijn ingevuld waar nodig en verbeteren de semantiek. Elementen zijn onderverdeeld in grotere en kleinere elementen.                | De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn niet ingevuld waar nodig en verbeteren de semantiek onvoldoende. Elementen zijn onderverdeeld in grotere en kleinere elementen.                                                                 | De semantisch juiste elementen werden niet of verkeerd gebruikt. De id's en classes zijn onvoldoende ingevuld. Elementen zijn onvoldoende onderverdeeld in grotere en kleinere elementen.                       |