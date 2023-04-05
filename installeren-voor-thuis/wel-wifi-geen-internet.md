---
layout: page
parent: Installeren voor thuis
title:  Wel wifi, geen internet 
---

# Wel wifi, geen internet

Op (in ieder geval) Windows 10 kun je deze situatie tegenkomen: je computer verbind prima met de myndr-wifi maar je hebt geen internet op je computer…
Wat kun je er aan doen?

De volgende oplossing kwam ik tegen op de Ziggo website 1 en bleek te werken voor een aantal klanten:

Klik onderin je scherm op het vergrootglas:

![Windows zoeken](https://permalink.myndr.net/knowledgebase/a9173fede59fe0023de6fc6adc4ada_t9rtbb.jpg)

Typ cmd in de zoekbalk:

![Windows type cmd](https://permalink.myndr.net/knowledgebase/966540d09ea31be41d24a2b3591982_3gvrv8.jpg)

Klik met je rechtermuisknop op Opdrachtpromt als die verschijnt:

![windows cmd found](https://permalink.myndr.net/knowledgebase/1045537ef36e85d22443b179b41d3c_61vkms.jpg)

Klik met je linkermuisknop op Als administrator uitvoeren:

![windows r-click](https://permalink.myndr.net/knowledgebase/1bc070b7af5bfb8cbe28d0511a4b29_wwsv92.jpg)

Klik op Ja:

![Windows als admin](https://permalink.myndr.net/knowledgebase/34b842fcbb052efe068923bd6b68c0_wku5qj.jpg)

Typ in: `netsh winsock reset` & druk op Enter

![windows terminal](https://permalink.myndr.net/knowledgebase/aedfc3ce9d216ab0a78fccb18877b8_14k4n14.jpg)

Herstart je computer.

Als het goed is zal je computer hierna geen problemen meer hebben met het verbinden met internet.
Mocht je problemen houden [neem dan contact met ons op](https://www.myndr.nl/contact). 


