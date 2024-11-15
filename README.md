# Styleguide

# Typografie
We maken gebruik van twee fonts, Inter en Jost.
De fonts worden geladen met behulp van @font-face, en de juiste fonts worden ingesteld via CSS-variabelen voor eenvoudig gebruik in de stylesheet.

# Typografie CSS Variabelen

--primary-font: "Inter" Inter, sans-serif, voor header tekst.
--secondary-font: "Jost" Jost, voor artikeltekst.
for more information on this topic: https://www.freecodecamp.org/news/css-units-when-to-use-each-one/#:~:text=The%20main%20reason%20why%20using,the%20size%20of%20the%20viewport.

# kleuren 
De kleuren van de huisstijl zijn opgebouwd uit de kleuren van het Antoni van Leeuwenhoek ziekenhuis logo, met een aanvullende set van donker rood voor contrast en leesbaarheid.

Primaire kleur (Rood): --primary-color en varianten voor lichtere tinten.
Secundaire kleur (lichte roze): --secondary-color-light en --secondary-color-dark voor een donkerdere versie.
Donkere roden: Inclusief verschillende donkere roden en verschillende backgrounds zoals  --primary-bg-batik: en --secondary-bg-batik: voor achtergronden.

# codeconventie
Om de CSS-structuur consistent en begrijpelijk te houden, gebruiken we een vaste naamgevingsconventie voor klassen met kebab case. Klassenamen volgen de structuur:

--elementtype-functie

elementtype: Het HTML-element of de rol, zoals button, heading, of link.
functie: De specifieke stijl of functie die het element vervult, zoals utility, quote, of article.
Bij voorbeeld: --filter-normal: Voor normale filters.


We hebben ook gebruik gemaakt van css nesting, cascade, and specificity.

For more information on this topic: https://developer.mozilla.org/en-US/docs/Glossary/Kebab_case , https://developer.mozilla.org/en-US/docs/Glossary/Camel_case#see_also

# Knoppen
De knoppen in de huisstijl zijn ontworpen voor specifieke functies en bevatten standaardstijlen voor interacties zoals hover. Voorbeelden zijn --button-hover voor het hover state van de knopjes.


## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

### code conventions

