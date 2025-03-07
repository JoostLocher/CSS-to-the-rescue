# CSS-to-the-rescue

## Week 1

**Assignment:** <br>Control panel

**Concept:** <br>Optie 1: Donkey Kong Multiscreen. Door de handheld multiscreen-console geïnspireerd, wil ik deze console (3D) namaken, waarbij je met een paar buttons, zoals Jump, Walk en Game A/B, DK op de twee schermen kunt besturen.
<img src="images/DK.jpeg" width="300" height="150">

Optie 2: Pokédex Console: Een console met één scherm waarop je één of meerdere Pokémon ziet. Met behulp van buttons en/of een slider kun je de achtergrond (regio's) en Pokémon wisselen.
<img src="images/pokedex.jpg" width="300" height="150">

**Uiteindelijke keuze:**<br> Na de feedback op vrijdag van week 1 heb ik ervoor gekozen om met de eerste optie (Donkey Kong Multiscreen) verder te gaan, maar dan in de stijl van de tweede optie, waarin meer harde kleuren en schaduwen werden gebruikt.

---

## Week 2

**Nieuw voor mij:**<br>
<ul>
    <li>3D transform doormiddel van <code>transform-style: preserve-3d;</code></li>
    <li>Cubus maken doormiddel van rotate en translate:<code>transform: rotateY(180deg) translateZ(calc(var(--base-z) / 2));</code></li>
    <li>dynamische maken cubus door custom var met calc te gebruiken<code>height: calc(calc(var(--base-y) / 2) / cos(45deg));</code></li>
</ul>

**Voortgang:**<br>
Deze week ben ik begonnen met het bouwen met een cubus door te spelen met 3D-transform. Dit heb ik maandag geprobeerd in een codepen en dinsdag in mijn eindproject gewerkt waar ik het ook dynamisch heb kunnen maken door middel van custom properties en het gebruik van math. Als laatst heb ik nog met Sanne gekeken hoe ik een beveld edge kon maken en heb ik hiervoor uitendelijk gebruik gemaakt van de cos(45) regel in een calc.

<img src="images/codepen3D.png" width="300" height="150">
<img src="images/css-week2-voortgang.png" width="300" height="150">

**Doel volgende week:**<br>
- Onderkant en bovenkant afmaken en stijlen.
- Knoppen en shermen toevoegen.


## Bronnen

<ul>
    <li>img DK: https://www.homecomputermuseum.nl/collectie/nintendo/nintendo-game-watch-donkey-kong-ii/</li>
    <li>img pokedex: https://nl.pinterest.com/pin/418060777921719484/</li>
    <li>3D cubus: https://codepen.io/shooft/pen/BaQLpQq?editors=1100, https://3dtransforms.desandro.com/cube</li>
    <li>3D transform: https://www.w3schools.com/css/css3_3dtransforms.asp</li>
    <li>...</li>
    <li>...</li>
</ul>
