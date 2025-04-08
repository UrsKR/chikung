---
layout: single
title: Das Centre Qigong
permalink: /cqg/
header:
  overlay_image: /assets/images/kick.jpg
---

Das Centre Qigong ist das Europäische Zentrum zur Ausbildung und Erforschung des Medizinischen Qigong. Das erste Centre Qigong entstand in Karlsruhe, dort unterrichtete Bernhard Mayer. Mittlerweile ist seine Schule umgezogen nach Germersheim.

### Standorte des Centre Qigong
Bernhards Lehrerschüler haben in ganz Deutschland eigene Schulen eröffnet, damit auch Du lernen kannst, Dich mit Qigong zu entspannen.

Hier findest du eine [Liste aller Standorte](https://www.centre-qigong.de/centreqigong/standorte.html).

### Befreundete Schulen
Neben unseren Standorten gibt es noch einige weitere Schulen, die ich empfehlen kann: Schulen, die ich selbst besucht habe, Schulen von früheren Lehrerschülern und Schulen von ehemaligen Standortleitern.

{% for friend in site.data.friends.friends %}
{{ friend.pin }} **{{ friend.city }}** – {{ friend.name }}  
<{{ friend.web }}>
{% endfor %}
