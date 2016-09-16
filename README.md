# PacManRheje
App voor PacMan Rheje.

Brainstorm:
Nodig:
1 App
1 Website
1 API voor de communicatie

-----------------------------------------------
App:
Voor PacMan Rheden is een app nodig die 2 modes kent.
Als je de app opend heb je de keuze of je een Runner of User bent, en welk karakter je bent/bestuurt.

Runner  | User
----------------
Pacman  | Pacman
Blinky  | Blinky
Inky    | Inky
Pinky   | Pinky
Clyde   | Clyde


Runner interface/functie:
- Grote pijl die aangeeft welke kant je op moet, deze pijl moet verranderen dmv:. FCM: high.
- Geeft iedere seconde of zo door wat zn huidige locatie is, naar de API.

User interface:
- 4 grote pijlen die ingedrukt kunnen worden om de runner aan te geven welke kant die op moet, deze handeling wordt verstuurt via een dmv:. FCM: high.

----------------------------------------------
Website:
Op de website kunnen de users zien waar de Runners zich bevinden.
Er moeten 2 versies zijn, 1 voor de User van Pacman 1 voor de users van de Ghosts.

Er moet een simpele website komen die google maps laat zien en deze update via javascript.
Op 1 versie van de kaart worden de posities van de ghosts weer gegeven, op de andere versie die van de ghosts en pacman.

Op de kaart van de ghosts users wordt 1x in de x minuten  de locatie van pacman door gegeven op de kaart, deze locatie blijft dan statisch op de kaart staat tot de volgende update over x minuten.

Op de kaart moet via een uitgebreid KML bestand de 'game'map worden getekend.

Extra:
automatich puntjes laten op eten ?!?!?!?

---------------------------------------------
API:
De Api zorgt voor de communicatie tussen App <> App en tussen App > website.

Het gaat om een makkelijk tussen door project, aangezien het een RP project is, hoeft hier geen login/key/etc. voor gebruikt te worden.
FCM calles kunnen via algemeen kanaal gestuurt worden zo dat er geen tokens gekoppeld hoeven te worden.


