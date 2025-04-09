---
title: Das Centre Qi Gong
permalink: /cqg/
---

Das Centre Qi Gong ist das Europäische Zentrum zur Ausbildung und Erforschung des Medizinischen Qi Gong. Das erste Centre Qi Gong entstand in Karlsruhe, dort unterrichtete Bernhard Maier. Mittlerweile ist seine Schule umgezogen nach Germersheim.

### Standorte des Centre Qi Gong
Bernhards Lehrerschüler haben in ganz Deutschland eigene Schulen eröffnet, damit auch Du lernen kannst, Dich mit Qi Gong zu entspannen.
Hier findest du uns:

{% for location in site.data.locations.locations %}
  {{ location.zip }} **{{ location.city }}** – {{ location.name }}  
  {% if location.web %} <{{ location.web }}>  
  {% elsif location.mail %} <{{location.mail}}>
  {% else %} {{ location.phone }}
  {% endif %}  
{% endfor %}


### Befreundete Schulen
Neben unseren Standorten gibt es noch einige weitere Schulen, die ich empfehlen kann: Schulen meiner Wegbegleiter und Schulen, die ich selbst besucht habe.

{% for friend in site.data.friends.friends %}
{{ friend.zip }} **{{ friend.city }}** – {{ friend.name }}  
<{{ friend.web }}>
{% endfor %}
