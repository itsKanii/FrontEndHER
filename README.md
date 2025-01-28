# FrontEndHER
Herkansing Frontend Development
Website: https://www.nasa.gov/

# Procesverslag
Voor u ligt het procesverslag voor het vak Frontend Development. Dit verslag is geschreven door een vierde jaars student, studerend aan de opleiding Communicatie Multimedia & Design aan de Hogeschool van Amsterdam.

De delivarables voor dit vak bestaan uit een procesverslag en twee verschillende webpagina's, uitgewerkt in nette vanilla HTML, CSS en Javascript.

Ik heb veel plezier beleefd aan het in praktijk brengen van de kennis die ik tijdens de studie heb opgedaan. Het schrijven van het procesboek was complex, maar dit heb ik met veel plezier geschreven. Vooral met de hulp van student assistent Christopher Willems heb ik veel inzicht gekregen in het coderen. Bij deze wil ik hem persoonlijk bedanken voor zijn hulp en ondersteuning tijdens dit project. Dit waardeer ik zeer.


## Jij

<details open>

### Auteur:
Kaa Leung Ho

#### Je startniveau:
Blauw

#### Je focus:
Responsive Design
 
</details>



## Je website

<details open>

### Je opdracht:
Ik ga twee webpagina's bouwen van de website www.nasa.gov.
Zie links: Homepagina
Zie rechts: ...Pagina

<p float="left">
  <img src="https://github.com/user-attachments/assets/f65bbe32-0f72-454d-8702-caeed4db7469" width="45%" />
  <img src="https://github.com/user-attachments/assets/f65bbe32-0f72-454d-8702-caeed4db7469" width="45%" />
</p>
 
</details>


## Breakdownschets (week 1)

<details>

<summary>In week 1 heb ik een breakdownschets gemaakt van de twee gekozen webpagina's.</summary>

  <img src="https://github.com/user-attachments/assets/ab70bb90-eccb-4441-a830-f600550166d6" width="45%" />

</details>



## Voortgang 1 (week 2)

<details>
 
<summary>In week 2 heb ik een poging gedaan om de eerste opzet van de website te maken in vanilla HTML.</summary>

### Stand van zaken
In week 2 heb ik een poging gedaan om een eerste opzet van de homepage in vanilla HTML te maken. Het structureren van de content in HTML was in het begin behoorlijk lastig. Het was namelijk al een tijdje geleden dat ik met code had gewerkt, en ik wist niet precies waar ik moest beginnen. Daarom besloot ik maar gewoon ergens te starten, en mijn gekozen website na te bouwen. Tijdens het voortgangsgesprek kwam ik er echter achter dat mijn code niet in orde was.

Ik had namelijk geen mobile-first-aanpak gehanteerd. Een studentassistent legde mij uit dat het belangrijk is om altijd mobile-first te beginnen. Bij een mobile-first-aanpak wordt vanaf het begin al een responsief ontwerp toegepast. Bovendien begreep ik dat het eenvoudiger is om vanuit een mobiele layout naar een  desktoplayout te schalen dan andersom.

### Agenda voor meeting
n.v.t.

### Verslag van meeting
- Altijd mobile-first beginnen bij het schrijven van code.
- Huiswerk voor volgende week: Homepagine in html (zover mogelijk) uitwerken.

</details>



## Voortgang 2 (week 3)

<details>
 
<summary>In week 3 heb ik geprobeerd de HTML elementen van de website zover mogeijk uit te werken in vanilla HTML.</summary>


### Stand van zaken
Bij deze voortgangsgesprek heb ik kritische feedback ontvangen over het schrijven van non-sematische elementen in mijn HTML document. Ik begreep niet goed waarom ik geen 'div' en 'classes' mocht gebruiken. Na uitgebreide uitleg van Danny de Vries begrijp ik nu eindelijk het belang van het gebruik van semantisch correcte HTML-elementen, zoals header, main en footer. Het gebruik van semantische elementen zorgt namelijk ervoor dat de content duidelijk georganiseerd is.

Dit is een voorbeeld van semantische incorrecte code:

```css
<div>
 <ul>
   <li><a href="#">Home</a></li>
   <li><a href="#">News & Events</a></li>
   <li><a href="#">Multimedia</a></li>
   <li><a href="#">NASA+</a></li>
   <li><a href="#">Missions</a></li>
 </ul>
</div>
```

Dit is een voorbeeld van semantische correcte code:

```css
<nav>
 <ul>
   <li><a href="#">Home</a></li>
   <li><a href="#">News & Events</a></li>
   <li><a href="#">Multimedia</a></li>
   <li><a href="#">NASA+</a></li>
   <li><a href="#">Missions</a></li>
 </ul>
</nav>
```

Tot slot heb ik ook het verschil geleerd tussen 'button' en 'a'. Een 'button' wordt gebruikt voor interacties binnen dezelfde webpagina, zoals het uitvoeren van een actie of het activeren van een javascript-element. Daarentegen wordt een 'a' gebruikt om door te navigeren naar een andere webpagina.

Ik heb 'button' toegepast voor het toggelen van de hamburger side menu:

```css
<button aria-label="Toggle Sidebar" aria-expanded="false">☰</button>
```

Ik heb 'a' toegepast voor het creëren van links op de homepagina:

```css
<nav>
 <a href="#">News & Events</a>
 <a href="#">Multimedia</a>
 <a href="#">NASA+</a>
</nav>
```

### Agenda voor meeting
n.v.t.

### Verslag van meeting
- Uitleg en de gedachtepunt omtrent het schrijven van semantische elementen in de HTML document.
- Geen 'div' of 'classes' gebruiken, maar CSS selectors.

</details>



## Toegankelijkheidstest (week 4)

<details>
<summary>In week 4 heb ik een toegankelijkheidstest uitgevoerd op mijn website samen met een medestudent op school.</summary>

### Bevindingen
Onderstaand worden de belangrijkste bevindingen vermeld die in de test naar voren kwamen:

#### De dropdown menu in de navigatiebalk (Desktop versie)
De screenreader werd ingezet om de toegankelijkheid en inclusiviteit van de website www.nasa.gov te meten. Hieruit bleek dat de navigatie in het dropdownmenu van de navigatiebalk op de homepagina niet optimaal is ontworpen voor gebruikers met bewegingsbeperkingen. Gebruikers kunnen namelijk niet eenvoudig met de pijltjestoetsen door het menu navigeren. Aangezien het dropdownmenu een groot aantal onderwerpen bevat, moeten gebruikers elk onderwerp individueel doorlopen. Dit maakt het niet mogelijk om direct de gewenste webpagina te selecteren, wat de gebruiksvriendelijkheid van de gebruiker belemmert.

  <img src="https://github.com/user-attachments/assets/efbde683-d8d2-4fb0-825a-7da790654185" width="45%" />

Het probleem kan worden opgelost door een duidelijke hiërarchische structuur op te zetten die het navigeren binnen het dropdownmenu eenvoudiger maakt. Dit houdt in dat gebruikers vanuit het hoofdmenu de mogelijkheid krijgen om een onderwerp te selecteren, waarna gebruikers direct toegang hebben tot de bijbehorende subonderwerpen of artikelen binnen die categorie. Daarnaast kan een optie worden toegevoegd waarmee gebruikers eenvoudig kunnen schakelen tussen andere hoofdonderwerpen.

#### Videos spelen continu af in een loop 
De website van NASA maakt veel gebruik van bewegende achtergronden bij artikelen op de homepagina. Deze video's worden continu afgespeeld en stoppen niet automatisch. Deze elementen kunnen de prestaties van de website negatief beïnvloeden, met name wanneer apparaten niet krachtig genoeg zijn om deze beelden soepel af te spelen.

Het probleem kan worden opgelost door minder belastende elementen, zoals GIF's, te gebruiken. Daarnaast is het ook een idee om gebruikers de mogelijkheid te geven om deze animaties handmatig uit te schakelen.

#### WCAG Checklist (door Beyza)

<p float="left">
  <img src="https://github.com/user-attachments/assets/2465882e-a649-484f-a027-2112721c2bcd" width="45%" />
  <img src="https://github.com/user-attachments/assets/604af183-2b95-44aa-84df-4626b44d713f" width="45%" />
  <img src="https://github.com/user-attachments/assets/a438ef5c-4002-445e-bf56-5c4a2dc84d89" width="45%" />
  <img src="https://github.com/user-attachments/assets/0a276d3b-0207-44fe-b6a0-1ccbef44a43b" width="45%" />
  <img src="https://github.com/user-attachments/assets/a09bfe8f-b61e-4bb9-a883-7c442235219d" width="45%" />
</p>

</details>



## Voortgang 3 (week 4)

<details>
<summary>In week 4 heb ik mijzelf geintroduceerd aan CSS, en leerde hoe media queries werkten.</summary>

### Stand van zaken
De mobiele versie is klaar, dus ik begin nu met de ontwikkeling van de desktopversie. Dit betekent dat ik eerst de benodigde HTML-elementen voor de desktopversie moet opzetten. Zodra deze klaar zijn, zal ik verdergaan met het toepassen van CSS. Christopher Willems heeft mij enorm geholpen bij het implementeren van media queries, waarmee content kan worden toegevoegd of verwijderd om de website responsief te maken voor verschillende schermformaten.
Daarnaast ga ik ook een beginnetje maken aan Javascript om het hamburgermenu interactief te maken.

  <img src="https://github.com/user-attachments/assets/b7a143d4-89dc-42d8-b8b1-1bcd05fa8264" width="45%" />

Mijn doel is nu om de HTML elementen voor de desktop versie te maken. Zie referentie:

  <img src="https://github.com/user-attachments/assets/e7fc943e-aa05-4431-92dd-643a2a9651f2" width="45%" />

Christopher Willems heeft mij uitleg gegeven hoe ik mijn website responsive kan maken door mediaqueries te gebruiken.
De 'min-width' element geeft aan hoe de webpagina hoort te gedragen, wanneer de webpagina een bepaalde minimale breedte heeft kunnen bereiken.
Ik heb onderstaand lopen oefenen met kleuren om deze veranderingen eenvoudig te kunnen zien.

```css
@media (min-width: 640px) {
    main {
        background-color: purple;
    }
}

@media (min-width: 800px) {
    main {
        background-color: yellow;
    }
}

@media (min-width: 1024px) {
    main {
        background-color: red;
    }
}
```

### Agenda voor meeting
n.v.t.

### Verslag van meeting
- De Mobile Versie is af, nu aan de slag met de Desktop Versie.
- Uitleg gekregen responsive design en bijbehorende media media query.

</details>



## Feedbackgesprek 1 (week 5)

<details>
<summary>Ik week 5 heb ik lopen erdiepen in CSS zoals Flesbox, Media Queries en Min-Width.</summary>

### Stand van zaken
Ik heb mij wezen verdiepen in responsive design en hoe elementen toegevoegd, verwijderd of verplaatst kunnen worden op de webpagina. Hierbij heb ik gewerkt met breakpoints om de lay-out dynamisch aan te passen aan verschillende schermformaten. Mijn website heeft drie responsieve ontwerpen met twee breakpoints.
De website begint met een minimale min-width van 600px. Het eerste breakpoint is ingesteld op 640px en het tweede breakpoint op 1024px. Hierdoor wordt de website optimaal weergegeven op diverse schermgroottes.
Daarnaast heb ik met flexbox lopen werken zodat ik content kan verschuiven aan de hand van diverse media queries.

Daarnaast heb ik een korte introductie gedaan tot Javascript. Mijn doel was om uit te zoeken hoe je de code kan schrijven, en hoe dit opgeroepen kan worden. 

### Kernpunten deze week
- Min-width zorgt ervoor dat de website een minimale dimensie kan behouden om het te laten werken.
- Ik heb lopen experimenteren met flexbox en media queries.
- Uitleg zoeken over Javascript op het internet

</details>



## Feedbackgesprek 2 (week 6)

<details>
<summary>In week 6 heb ik thuis gewerkt aan CSS en Javascript. Mijn doel was om de Homepagina te kunnen finaliseren.</summary>

### Stand van zaken
Deze week was erg druk geweest voor mij, omdat ik een herkansing had voor een ander vak die ik echt moest halen. Hierdoor kon ik helaas niet deelnemen aan de feedbackgesprekken op school. Om dit te compenseren, heb ik mezelf verdiept in online bronnen voor het finaliseren van de desktop versie. Christopher Willems heeft mij een hele handige open-source website aanbevolen om theorieën en documentatie op te zoeken, namelijk MDN Web Docs.

Ik heb deze week veel aan de homepagina gezeten. Ik wil de mediaqueries afmaken, zodat ik aan de hamburger menu kan zitten. Dit betekent dat ik dieper in Javascript moest duiken.
Daarnaast ben ik erachter gekomen dat mijn initiele website voor de tweede webpagina is verdwenen, omdat de website van Nasa.gov constant verandert. Ik heb uiteindelijk een nieuwe webpaginam moeten zoeken om het na te maken.

  <img src="https://github.com/user-attachments/assets/56211f28-571c-4ee3-a578-5a20aadf8fd2" width="45%" />

### Kernpunten deze week
- Finaliseren van de Homepagina.
- Meer wezen verdiepen in CSS en Javascript
- Zoeken van een nieuwe tweede webpagina.
- Begin gemaakt aan de tweede webpagina.

</details>

## Eindgesprek 

<details>
<summary>In de laatste week heb ik alle puntjes op de i proberen te zetten.</summary>

### Stand van zaken
Door de herkansing kon ik ook niet deelnemen aan aan het eindgesprek. Ik heb contact gezocht met Christopher Willems. Samen hebben wij lopen kijken naar mijn code. 

### Screenshot(s)

hier screenshot(s) van je eindresultaat

</details>



## Bronnenlijst

<details open>
<summary>Onderstaan zie je de bronnen die ik heb gebruikt om deze webpagina's te maken.</summary>

- Aria-label: https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-label
- Article: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article
- Flexbox: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Flexbox
- Images/ Logo: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img
- Javascript: https://dlo.mijnhva.nl/content/enforced/609316-FDMCI-2000FED121-DMCI-CMD-2425-1/FED%2024-25%20-%20Blok%202%20-%20Intro%20JS%203-stap.pdf
- Semantics: https://developer.mozilla.org/en-US/docs/Glossary/Semantics
- Toggle True/Flase: https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList/toggle
- Media Query Fundamentals: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries

</details>
