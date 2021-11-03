# Rapportage webtoegankelijkheid-test voor openbare bibliotheek van Amsterdam
[live pagina 🌐](https://www.oba.nl/agenda.html)
![preview oba op digital screen](/assets/unknown.png)

*Dit document is een webtoegankelijkheid-test volgens de Web Content Accessibility Guidelines (WCAG). Een consistente rapportage helpt bij het uitvoeren van een evaluatie en zorgt er voor dat verschilelnde tests kunnen worden vergeleken.*

Datum webtoegankelijkheid-test: 03/11/2021

Webtoegankelijkheid-test uitgevoerd door: Beau & Matthijs

## Inhoudsopgave

  * [Samenvatting](#samenvatting)
  * [Achtergrond bij de evaluatie](#achtergrond-bij-de-evaluatie)
  * [Afbakening](#afbakening)
  * [Beoordelaars](#beoordelaars)
  * [Beoordelingsproces](#beoordelingsproces)
  * [Testresultaten en aanbevelingen](#testresultaten-en-aanbevelingen)
  * [Referenties](#referenties)
  * [Bijlagen](#bijlagen)
  * [Licentie](#licentie)

## Samenvatting

Dit rapport beschrijft in hoeverre de website OBA agendapagina overeenstemt met de *Web Content Accessibility Guidelines (WCAG)* van het W3C. Na de achtergrondinformatie en afbakening van de test worden beoordelaars, beoordelingsproces en testresulltaten beschreven. 

Conclusie van deze test luidt dat de Openbare Bibliotheek Amsterdam website dichtbij voldoet aan de WCAG 2.1, op niveau AA. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.

## Achtergrond bij de evaluatie

De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op 3-11-2021. De website kan ondertussen aangepast zijn.

## Afbakening

OBA agendapagina

Informatie om deel te nemen aan de informatie samenleving zo laagdrempelig te maken als mogelijk is.

https://www.oba.nl/agenda.html

De agenda pagina is zowel handmatig beoordeeld als met semi-geautomatiseerde tools.

03/11/2021

HTML, CSS en javascript


## Beoordelaars

{Naam van de beoordelaar of het beoordelingsteam}

{Organisatie van de beoordelaars}

{Contactinformatie van de beoordelaar(s)}

{Expertisegebied van de beoordelaars op basis van naamgeving in de referentie: “Informatie over het gebruik van gecombineerde expertise voor het evalueren van webtoegankelijkheid”}

{Niveau van natuurlijke taal/talen waarin de beoordelaar(s) communiceert/communiceren}

## Beoordelingsproces

{Benoem het WCAG 2.1 niveau waarvoor de beoordeling is uitgevoerd, bv. WCAG 2.1 Niveau A, AA of AAA}

{Benoem de beoordelings- en evaluatietools en versies van de tools die gebruikt zijn}

{Beschrijf hoe handmatige beoordeling is uitgevoerd, bv. usability test of toegankelijkheidstest aan de hand van A11Y Project-checklist}

## Testresultaten en aanbevelingen

{Samenvatting van testresultaten, bv. deze website {voldoet/ voldoet niet/ is dichtbij aan voldoen} aan de WCAG 2.1, op niveau A, AA of AAA.}

### Sterke punten
{Samenvatting van de de sterke punten ...}

### Ontoegankelijke punten
{Samenvatting van ontoegankelijke punten ...}

### Checklist 

{Beschijf de resultaten van de hele test op basis van de A11Y Project-Checklist}

##### Content
  * Het taalgebruik is duidelijk en is eenvoudig te lezen.
  * De inhoud van  de button, a en label elementen zijn uniek en bevatten beschrijvende text. 
  * Op de website is alleen geschikt voor left-to-right talen. Op de website kun je kiezen tussen Nederlands en Engels.


##### Global code
![preview oba op digital screen](/assets/html-checker.png)
  * Een document mag niet zowel een meta-element met een http-equiv-attribuut waarvan de waarde content-type is, als een meta-element met een charset-attribuut bevatten.
``` 
<meta charset="utf-8">
```
 
  * Een meta-element met een http-equiv-attribuut waarvan de waarde X-UA-Compatible is, moet een content-attribuut hebben met de waarde IE=edge.
``` 
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
```
 
  * Attribuuttype is op dit moment niet toegestaan bij element selectie.
 ```
 <select id="pagination-selector" type="select" name="pageNumber">
 ```
 
##### Keyboard
  * De interface en inhoud kan worden genavigeerd doormiddel van het toetsenbord.
  * Er is een zichtbare focusstijl voor de geselecteerde elementen via toetsenbordinvoer.
  * De focusvolgorde van het toetsenbord komt overeen met de visuele lay-out.

##### Images
  * Zorg ervoor dat alle img-elementen een alt-attribuut hebben.
  * Bij bijna alle img-elementen van agenda pagina ontbreken de alt-attributen. Alleen het logo van OBA bevat een alt-attribuut.
   ```
<img src="/content/dam/logo/oba-logo.png" alt="Openbare Bibliotheek Amsterdam">
```

##### Headings
* Er is geen h1.
* De h2 elementen hebben niet de zelfde ```font-size```. (had handig geweest als de grootste text een h1 zou zijn)
* De headings beschrijven goed de content van de pagina.
* Er is verder een logische opbouw omdat de geneste headings een waarde hebben van h3.

##### Lists
* De nav, filter-nav, agenda & footer-nav bevatten allemaal een unordered list.
* De pagina-nav bestaat uit een ordered list.
* Alle lists zijn correct genest.

##### Controls
* Alle links & knoppen zijn toegankelijk voor screenreaders en keyboard navigatie.

##### Tables
n.v.t.


{Schrijf per check wat er uit de test is gekomen}

{Neem links op naar de WCAG 2.1 succescriteria en technieken voor de ontoegankelijke punten}

{Voeg per check specifieke rapportage(s), of links naar rapportage(s) toe in de Wiki, bv. screenshots van tests}

{Schrijf per check aanbevelingen voor het verbeteren van ontoegankelijke punten}

{Beschrijf of verwijs per check naar een programma voor het monitoren van webstite toegankelijkheid, her-beoordeling aan de hand van beoordelingsinstrumenten etc.}

### Resultaten Usability test

{Beschrijf per pagina de bevindingen uit jouw usability test in het lab.}

## Referenties

Referenties welke gebruikt zijn bij de webtoegankelijkheid-test. Deze referenties zijn allen in het Engels:

- [Overzicht en introductie van de Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/intro/wcag)
- [De complete Web Content Accessibility Guidelines 2.1 (WCAG)](https://www.w3.org/TR/WCAG21/)
- [Technieken voor WCAG 2.1](https://www.w3.org/WAI/WCAG21/Techniques/)
- [Bronnen voor beoordeling van webtoegankelijkheidsevaluatie ](http://www.w3.org/WAI/eval/)
- [Tools lijst voor semi-geautomatiseerde beoordeling van webtoegankelijkheid](https://www.w3.org/WAI/ER/tools/)
- [Informatie over het gebruik van gecombineerde expertise voor het evalueren van webtoegankelijkheid](https://www.w3.org/WAI/eval/reviewteams)
- [A11Y Project Checklist](https://www.a11yproject.com/checklist/)

{Vul aan waar nodig, haal weg wat niet relevant is}

## Bijlagen

{Geef een opsomming van de bijlagen, zoals links naar rapportages, screenshots en uitleg in de Wiki}


[Einde van het template]

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
