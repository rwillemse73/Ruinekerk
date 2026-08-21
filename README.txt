MODULAIRE LOCATIE-APP — OUDE NIEDORP

Structuur:
index.html = GPS/app-logica
locaties.json = lijst met locaties en GPS
content/ = afzonderlijke inhoud per locatie

Nieuwe locatie toevoegen:
1. Voeg een object toe aan locaties.json:
   {"id":"nieuweplek","name":"Naam","lat":0,"lon":0,"file":"nieuweplek.html"}
2. Maak content/nieuweplek.html.
3. Upload beide bestanden naar GitHub.
4. De index hoeft niet aangepast te worden.

De app ondersteunt een willekeurig aantal locaties en gebruikt een triggerzone van 250 meter.
