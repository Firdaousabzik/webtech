# Labo 2 - reflecties

Naam: Firdaous Abzik

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: Selecteert alle links in lijstitems van een ongeordende lijst binnen de navigatie van de header.
- b. `article > p`: Selecteert alle paragrafen die rechtstreeks binnen een article-element staan.
- c. `.uren li:nth-child(3)`: Selecteert elk lijstitem dat het derde kind is van zijn ouder en binnen een element met de class uren staat.
- d. `h2 ~ p`: Selecteert alle paragrafen die na een h2 staan en dezelfde ouder hebben.
- e. `.rassen li:first-child`: Selecteert alle lijstitems die het eerste kind van hun ouder zijn en binnen een element met de class rassen staan.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |groen |enigste keuze |groen |juist |
| 2 |blauw |tweede keuze |blauw |juist |
| 3 |rood |door opvallend |rood |juist |
| 4 |groen  |door > |rood |fout |
| 5 | blauw|tweede keuze |blauw |juist |
| 6 |blauw |-tekst |blauw |juist |
| 7 |rood |enige keuze |rood |juist |
| 8 |rood |enige keuze |blauw |fout |
| 9 |rood |!important |rood |juist |
| 10 |groen |door geen ; na font-size |groen |juist |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
Bij vraag 4 door >
Bij vraag 8 door

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
Ik heb de selector `nav a` gebruikt omdat deze alle links binnen de navigatie selecteert. Een class is niet nodig, omdat ik de links rechtstreeks via de HTML-structuur kan selecteren.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
De regel voor de slogan kostte mij het meeste tijd. Eerst werd de tekst niet kleiner, grijs en cursief zoals in het voorbeeld. Uiteindelijk heb ik gecontroleerd of de class `.slogan` correct werd gebruikt en of de CSS in het juiste bestand stond.

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
Ik heb gekozen voor de achtergrondkleur (#f5f5f5), tekstkleur (#333333) en hoofdkleur (#2c3e50). De achtergrondkleur zorgt voor een rustige uitstraling, de tekstkleur maakt alles goed leesbaar en de hoofdkleur gebruik ik voor de header en footer.
- Wat verandert er in je site als je één token wijzigt?
Als ik één token wijzig, veranderen alle elementen die dat token gebruiken automatisch mee. Zo kan ik bijvoorbeeld de achtergrondkleur op meerdere plaatsen tegelijk aanpassen.

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
