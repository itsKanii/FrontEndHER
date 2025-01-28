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
<summary>uitwerken na afloop 2e werkgroep</summary>

### de hele pagina: 
<img src="https://github.com/user-attachments/assets/5cc6ffc6-309b-4325-bdbc-931a4fbeb781
" width="375px" alt="breakdown van de hele pagina">

### dynamisch deel (bijv menu): 
<img src="images/dummy-plaatje.jpg" width="375px" alt="breakdown van een dynamisch deel">

### wellicht nog een dynamisch deel (bijv filter): 
<img src="images/dummy-plaatje.jpg" width="375px" alt="breakdown van nog een dynamisch deel">

<p float="left">
  <img src="https://github.com/user-attachments/assets/f65bbe32-0f72-454d-8702-caeed4db7469" width="45%" />
  <img src="https://github.com/user-attachments/assets/f65bbe32-0f72-454d-8702-caeed4db7469" width="45%" />
  <img src="https://github.com/user-attachments/assets/f65bbe32-0f72-454d-8702-caeed4db7469" width="45%" />
</p>



</details>



## Voortgang 1 (week 2)

<details>
 
<summary>In de tweede week heb ik een poging gedaan om een eerste opzet van de homepage in vanilla HTML te maken.</summary>

### Stand van zaken
Het structureren van de content in HTML was in het begin behoorlijk lastig. Het was namelijk al een tijdje geleden dat ik met code had gewerkt, en ik wist niet precies waar ik moest beginnen. Daarom besloot ik maar gewoon ergens te starten, en mijn gekozen website na te bouwen. Tijdens het voortgangsgesprek kwam ik er echter achter dat mijn code niet in orde was.

Ik had namelijk geen mobile-first-aanpak gehanteerd. Een studentassistent legde mij uit dat het belangrijk is om altijd mobile-first te beginnen. Bij een mobile-first-aanpak wordt vanaf het begin al een responsief ontwerp toegepast. Bovendien begreep ik dat het eenvoudiger is om vanuit een mobiele layout naar een  desktoplayout te schalen dan andersom.

### Agenda voor meeting
n.v.t.

### Verslag van meeting
- Altijd mobile-first beginnen bij het schrijven van code.
- Huiswerk voor volgende week: Homepagine in html (zover mogelijk) uitwerken.

</details>



## Voortgang 2 (week 3)

<details>
 
<summary>In de derde week heb ik een poging gedaan om de eerste opzet van de homepage zover mogeijk uit te werken in vanilla HTML.</summary>


### Stand van zaken
Bij deze voortgangsgesprek heb ik kritische feedback ontvangen over het schrijven van non-sematische elementen in mijn HTML document. Ik begreep niet goed waarom ik geen 'div' en 'classes' mocht gebruiken. Na uitgebreide uitleg van Danny de Vries begrijp ik nu eindelijk het belang van het gebruik van semantisch correcte HTML-elementen, zoals header, main en footer. Het gebruik van semantische elementen zorgt namelijk ervoor dat de content duidelijk georganiseerd is.

Tot slot heb ik ook het verschil geleerd tussen 'button' en 'a'. Een <button> wordt gebruikt voor interacties binnen dezelfde webpagina, zoals het uitvoeren van een actie of het activeren van een javascript-element. Daarentegen wordt een <a> gebruikt om door te navigeren naar een andere webpagina.

### Agenda voor meeting
n.v.t.

### Verslag van meeting
- Uitleg en de gedachtepunt omtrent het schrijven van semantische elementen in de HTML document.
- Geen 'div' of 'classes' gebruiken, maar CSS selectors.

</details>



## Toegankelijkheidstest (week 4)

<details>
<summary>In week 4 heb ik een toegankelijkheidstest samen met een medestudent laten uitvoeren op mijn website.</summary>

### Bevindingen
Onderstaand worden de belangrijkste bevindingen, die in de test naar voren kwamen, vermeld:

#### De dropdown menu in de navigatiebalk (Desktop versie)
De screenreader werd ingezet om de toegankelijkheid en inclusiviteit van de website www.nasa.gov te meten. Hieruit bleek dat de navigatie in het dropdownmenu van de navigatiebalk op de homepagina niet optimaal is ontworpen voor gebruikers met bewegingsbeperkingen. Gebruikers kunnen namelijk niet eenvoudig met de pijltjestoetsen door het menu navigeren. Aangezien het dropdownmenu een groot aantal onderwerpen bevat, moeten gebruikers elk onderwerp individueel doorlopen. Dit maakt het niet mogelijk om direct de gewenste webpagina te selecteren, wat de gebruiksvriendelijkheid van de gebruiker belemmert.

<img width="1278" alt="Schermafbeelding 2025-01-26 om 23 24 34" src="https://github.com/user-attachments/assets/efbde683-d8d2-4fb0-825a-7da790654185" />

Het probleem kan worden opgelost door een duidelijke hiërarchische structuur op te zetten die het navigeren binnen het dropdownmenu eenvoudiger maakt. Dit houdt in dat gebruikers vanuit het hoofdmenu de mogelijkheid krijgen om een onderwerp te selecteren, waarna ze direct toegang hebben tot de bijbehorende subonderwerpen of artikelen binnen die categorie. Daarnaast kan een optie worden toegevoegd waarmee gebruikers eenvoudig kunnen schakelen tussen andere hoofdonderwerpen.

#### Videos spelen continu af in een loop. 
De website van NASA maakt veel gebruik van bewegende achtergronden bij artikelen op de homepagina. Deze video's worden continu afgespeeld en stoppen niet automatisch. Dergelijke elementen kunnen de prestaties van de website negatief beïnvloeden, vooral wanneer het apparaat niet krachtig genoeg is om deze beelden soepel af te spelen.

Het probleem kan worden opgelost door minder belastende elementen, zoals GIF's, te gebruiken. Daarnaast is het ook een idee om gebruikers de mogelijkheid te geven om deze animaties handmatig uit te schakelen.

</details>



## Voortgang 3 (week 4)

<details>
<summary>HTML verder uitwerken en begin maken aan CSS.</summary>

### Stand van zaken
De mobiele versie is klaar, dus ik begin nu met de ontwikkeling van de desktopversie. Dit betekent dat ik eerst de benodigde HTML-elementen voor de desktopversie moet opzetten. Zodra deze klaar zijn, zal ik verdergaan met het toepassen van CSS. Christopher Willems heeft mij enorm geholpen bij het implementeren van media queries, waarmee content kan worden toegevoegd of verwijderd om de website responsief te maken voor verschillende schermformaten.
Daarnaast ga ik ook een beginnetje maken aan Javascript om het hamburgermenu interactief te maken.

<img width="626" alt="Schermafbeelding 2025-01-27 om 00 41 47" src="https://github.com/user-attachments/assets/e7f76c64-22d0-4029-881a-33e162a5c804" />
<img width="626" alt="Schermafbeelding 2025-01-27 om 00 43 28" src="https://github.com/user-attachments/assets/32379fd4-e73c-4d06-91d2-f9391eec6631" />

### Agenda voor meeting
n.v.t.

### Verslag van meeting
- De Mobile First aanpak is af en goedgekeurd.
- Uitleg gekregen responsive design en bijbehorende media media query.

</details>



## Feedbackgesprek 1 (week 5)

<details>
<summary>Verdiepen in meer CSS</summary>

### Stand van zaken
Ik heb mij wezen verdiepen in responsive design en hoe elementen toegevoegd, verwijderd of verplaatst kunnen worden op de webpagina. Hierbij heb ik gewerkt met breakpoints om de lay-out dynamisch aan te passen aan verschillende schermformaten. Mijn website heeft drie responsieve ontwerpen met twee breakpoints.
De website begint met een minimale min-width van 600px. Het eerste breakpoint is ingesteld op 640px en het tweede breakpoint op 1024px. Hierdoor wordt de website optimaal weergegeven op diverse schermgroottes.

### Kernpunten deze week
- Min-width zorgt ervoor dat de website een minimale dimensie kan behouden om het te laten werken.
- Niet alle elementen worden meegeschaald met de responsiveness van de website.
- Uitleg gekregen Javascript.

</details>



## Feedbackgesprek 2 (week 6)

<details>
<summary>Thuiswerken aan CSS en Javascript</summary>

### Stand van zaken
Deze week was erg druk geweest voor mij, omdat ik een herkansing had voor een ander vak die ik echt moest halen. Hierdoor kon ik helaas niet deelnemen aan de feedbackgesprekken op school. Om dit te compenseren, heb ik mezelf verdiept in online bronnen voor het finaliseren van mijn website. Christopher Willems heeft mij een hele handige open-source website aanbevolen om theorieën en documentatie op te zoeken, namelijk MDN Web Docs.

### Kernpunten deze week
- Min-width zorgt ervoor dat de website een minimale dimensie kan behouden om het te laten werken.
- Niet alle elementen worden meegeschaald met de responsiveness van de website.
- Uitleg gekregen Javascript.

</details>

## Eindgesprek 

<details>
<summary>Puntjes op de i zetten</summary>

### Stand van zaken
Door de herkansing kon ik ook niet deelnemen aan aan het eindgesprek. Ik heb contact gezocht met Christopher Willems. Samen hebben wij naar mijn code gekeken.

### Screenshot(s)

hier screenshot(s) van je eindresultaat

</details>















## Bronnenlijst

<details open>
<summary>continu bijhouden terwijl je werkt</summary>

Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg).

1. bron 1
2. bron 2
3. ...

</details>
