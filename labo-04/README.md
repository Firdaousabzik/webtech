# Labo 4 - reflecties

Naam: (jouw naam)

## 1. Drie kolommen

- Op welk element staat `display: flex`, en op welke elementen staat `flex`?
display: flex staat op main en op de drie div-elementen om de cijfers te centreren
- Waarom staan die twee niet op hetzelfde element?
flex: 1 en flex: 2 staan op de div-elementen om hun breedte te verdelen.
## 2. Navigatiebalk

- Welke property verdeelt de ruimte langs de hoofdas, en welke lijnt uit op de kruisas?
justify-content: space-between; verdeelt de beschikbare ruimte tussen het logo en de navigatie. align-items: center; centreert de elementen verticaal.
- Wat gebeurt er met de links als je `gap` vervangt door `margin-right` op elke `li`?
Dan krijgt ook het laatste lijstitem een rechtermarge, waardoor er onnodige extra ruimte ontstaat. gap voegt alleen ruimte tussen de items toe.

## 3. Mondriaan

- Welke twee vlakken moest je expliciet plaatsen, en waarom volstond de impliciete vulling voor de andere vier?
Lila en olijfgroene vlak, omdat ze meerdere kolommen innemen. Voor de juiste indeling hebben we ook de positities van bruin en marine vastgelegd. Omdat CSS Grid de overige elementen automatisch in de beschikbare cellen kan plaatsen.

- Waarom is `gap` hier beter dan een border op elk vlak?
omdat gap de tussenruimte maakt en de blauwe achtergrond van het schilderij zichtbaar laat worden. Met border krijgt elk vlak afzonderlijk een rand.

## 4. Trap

- Wat zie je als je de `grid-row`-declaraties weghaalt, en waarom?
De vier treden komen naast elkaar op de eerste rij te staan, omdat CSS Grid de rijen dan automatisch bepaalt.

- Wat betekent `grid-column: 4 / -1` voor de laatste trede, en waarom werkt het hier ook?
De trede begint bij rasterlijn 4 en eindigt bij de laatste rasterlijn. Omdat het raster vier kolommen en vijf rasterlijnen heeft, neem de trede precies de vierde kolom in.

## 5. Dierenasiel Zonnehoek

- Hoeveel layoutcontainers telt deze pagina, en welk gereedschap koos je voor elk?
Er zijn er 9
=> body: grid(1)
=> header: Flexbox(1)
=> nav ul: Flexbox(1)
=> .kaarten: Grid(1)
=> .kaart: Flexbox(5)

- Verklein het venster tot de helft: wat breekt er, en in welk hoofdstuk wordt dat opgelost?
Verklein eerst zelf je browservenster. Je zal waarschijnlijk zien dat de navigatie te breed wordt en de kaarten te smal worden. Dit wordt .

## Thuis: B4.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
