# Labo 3 - reflecties

Naam: Firdaous

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?

Ik heb de standaardinstellingen list-style en padding aangepast. Met list-style: none verwijder ik de bolletjes en met padding: 0 verwijder ik de inspringing van de lijst
- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?

Als ik het browservenster hoger maak, worden de kleurenbalken ook hoger. Dit komt doordat ik `height: 50vh` gebruik. Elke balk neemt altijd 50% van de hoogte van het browservenster in.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?

text-align: center = centreert de tekst
margin: 0 auto centreert de kolom horizontaal

- Waarom werkte de padding op de knop pas na `display: inline-block`?

Omdat inline-block ervoor zorgt dat de knop zich als een box gedraagt, waardoor de padding boven en onder ook ruimte inneemt in de lay-put

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?

de visuele breedte is 15rem, omdat box-sizing: border-box ervoor zorgt dat de padding en border inbegrepen zijn in de opgegeve, breedte en er biet extra bij worden opgeteld.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?

Omdat het ouderelement (mainà)een vaste hoogte van 90vh heeft. Daardoor kan de browser de 70% berekenen.

- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?
Op de breedte van het ouderelement, niet op de hoogte. Dit geldt ook voor de boven- en ondermarge

## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?

Ik gebruikte min-height: 80vh; zodat main minstens 80% van de schermhoogte inneemt, maar groter kan worden als er meer inhoud is.

- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?

Er ontstaat witruimte tussen de twee inline-block elementen. Daardoor passen de twee helften van 50% mogelijk niet meer naast elkaar en kan de afbeelding naar de volgende regel springen.

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. CSS-tokens: De fout --lettertpe verbeterd naar --lettertype, zodat de variabele correct werkt.
2. HTML-structuur: Een <main>-element toegevoegd aan index.html, zodat de gecentreerde leeskolom correct wordt toegepast.
3. CSS-reset: reset.css vóór stijl.css gekoppeld aan de drie HTML-pagina's.
