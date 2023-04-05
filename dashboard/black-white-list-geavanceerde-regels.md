---
layout: page
parent: Dashboard
title:  Black & white list geavanceerde regels 
---

# Black & white list geavanceerde regels

Dit artikel legt de meer geavanceerde filtermethodes van de black & white list uit.

### Alternatieven
Als je veel black/white lists hebt, kan het handig zijn om verschillende te combineren tot 1 regel. Dit kan op de volgende manier: zet tussen de alternatieven een | symbool, en zet haken om de alternatieven heen. Je kunt dit vaak ook bereiken door niet voor volledige url of domein te kiezen, maar voordeel van met alternatieven werken is dat je specifiek kunt zijn. Je loopt dan minder risico dat ongewenste sites ook mogen of juist worden geblokkeerd.

Voorbeelden met domeinen (kies criterium** Volledig domein** om zo specifiek mogelijk te zijn):
www.oefenen.nl en images.oefenen.nl samen: (www|images).oefenen.nl
oefenen.nl en www.oefenen.nl samen: (www.|)oefenen.nl

Voorbeeld met url (kies criterium Volledige url om zo specifiek mogelijk te zijn):
https://www.oefenen.nl/oefentoets/groep-6, 7 en 8 samen: https://www.oefenen.nl/oefentoets/groep-(6|7|8)
https://www.oefenen.nl/oefentoets/groep-8 en www.oefenen.nl/luistertoets/ samen:
https://www.oefenen.nl/(oefentoets/groep-8|luistertoets/)

### Voorbeeld met geneste alternatieven:
https://www.oefenen.nl/oefentoets/groep-6, 7,8 en www.oefenen.nl/oefentoets/begin samen:
https://www.oefenen.nl/oefentoets/(begin|groep-(6|7|8))

### Handig om te weten
Bij urls hoef je niet perse https:// toe te voegen. Echter, als je het WEL doet, dan is de regel specifiek. Dus https://www.oefenen.nl werkt NIET op http://www.oefenen.nl. Maar www.oefenen.nl, of //www.oefenen.nl of ://www.oefenen.nl werken zowel op http als https.
Je kunt dus ook bijzondere protocols toevoegen op de expliciete wijze:  ftp://oefenen.nl. 
Ook hier kun je alternatieven gebruiken: (ftp|http(s|))://(www.)oefenen.nl/.
**Pas op:** bij urls wordt op dit moment de automatische toevoeging van http:// NIET gedaan als er alternatieven in het domein staan! Dit staat op ons verlanglijstje.
 


