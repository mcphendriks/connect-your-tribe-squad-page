
# Titel
Ontwerpen en bouwen aan een squad page(overzichtspagina) met Node, EJS, Express en data uit de [whois.fdnd.nl](https://whois.fdnd.nl/) REST API voor de opleiding FDND (sprint 7)

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
User Story: Als FDND-student wil ik een filteroptie genaamd "Ambities" hebben, zodat ik kan filteren op de toekomstige droomloopbaan van medestudenten. Met deze filteroptie kan ik gemakkelijk de toekomstige droomloopbaan vinden van degenen die vergelijkbare ambities heeft.

<img width="1437" alt="Screenshot 2023-02-25 at 08 49 08" src="https://user-images.githubusercontent.com/106346778/221345648-2d84eaaa-a465-4dae-9381-b3569ffc53b3.png">
<!-- Voeg een link toe naar Github Pages 🌐-->

## Kenmerken
Node.js
Node is een Javascript omgeving die wordt gebruikt om javascript server-side te bouwen.

Express
Express is een framework voor Node, die helpt om eenvoudig en snel te bouwen. Express biedt een gestructureerde manier om routes te definiëren.

EJS
EJS is een JavaScript-templating het zorgt ervoor om HTML-templates eenvoudige te make en te hergebruiken met behulp van JavaScript, het haalt gegevens op die zijn opgeslagen in een server-side database (Node.js) Tip: Je kan ook client-side werken met EJS en je kunt variabelen, loops, conditionals en andere JavaScript-functies gebruiken in EJS.

JSON
JSON is een gegevensindeling voor het uitwisselen van gegevens tussen client en server.

Node.js en Express werken samen om een server te bouwen voor het verwerken van browserverzoeken en terugsturen van HTML-inhoud. EJS werkt samen met Express om dynamische inhoud te genereren op basis van de gegevens van de server. Express biedt structuur voor routes en middleware en maakt EJS-rendering mogelijk. Node biedt de runtime-omgeving voor deze webapplicaties op een server. Express

## Installatie Node.js
1. installeer de Node ontwikkelomgeving, kies 18.14.0 LTS

2. Voer in de terminal het commando npm install uit (Je gebruikt NPM, om een express inclusief alle afhankelijkheden te installeren.

3.  Voer in de terminal het commando npm start uit. er verschijnt over het opstarten van de server: Application started on http://localhost:8000, 

<!-- Bij Installatie staat stap-voor-stap beschreven hoe je de development omgeving moet inrichten om aan de repository te kunnen werken. -->

## Bronnen

#### Materiaal analysefase
- [WHOIS API](https://whois.fdnd.nl)
- [Learn about projects on Github](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

#### Materiaal bouwfase

- [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)
- [EJS - Embedded JavaScript templating](https://ejs.co)
- [Control Flow in JavaScript: Loops](https://dev.to/pszponder/control-flow-in-javascript-loops-26bd)

#### Materiaal integreerfase

- [Cyclic Hosting](https://www.cyclic.sh/)

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
