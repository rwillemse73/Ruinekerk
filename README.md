# Ruïnekerk / kerk-app – volledige proef v1

Deze versie is een zelfstandige mobiele webapp met losse locatiebestanden.

## Structuur

```text
index.html
locaties.json
locaties/
  ruinekerk.html
  skarpet.html
images/
```

## Functies
- interactieve kaart
- echte GPS
- virtuele testpositie
- locaties binnen 500 meter
- verhaalzone binnen 250 meter
- losse contentbestanden
- bestaande locaties bewerken
- nieuwe locatie toevoegen
- restaurant/café/hotel/eigen herinnering
- persoonlijke bezoekstatus
- beoordeling
- dagboeknotitie
- foto-selectie als voorbereid veld

## Opslag
De proef gebruikt lokale browseropslag (`localStorage`). Dat is geschikt om de werking op één telefoon te testen. Voor synchronisatie tussen apparaten of permanente opslag is later een database/backend nodig.

## GPS
De twee locaties gebruiken in deze proef testcoördinaten rond de testpositie. Ze zijn niet bedoeld als definitieve geografische coördinaten.
