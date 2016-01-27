# CBS Gebiedsindelingen

In deze repository staan TopoJSON bestanden van de CBS gebiedsindelingen. De bron van deze
bestanden is het [nationaal georegister](http://geodata.nationaalgeoregister.nl/). Daaruit kan je
ook de complete lijst van beschikbare indelingen [opvragen](http://geodata.nationaalgeoregister.nl/cbsgebiedsindelingen/wms?service=WFS&request=GetCapabilities).

De bestanden zijn eerst van het `EPSG:28992` SRS (Spatial Reference System) omgezet naar `EPSG:4326`.

Hierna zijn de bestanden omgezet naar TopoJSON. Hierbij is de CBS *code* voor een gebied bewaard
gebleven (`statcode`), net zoals een paar andere velden (`statnaam`, `rubriek`).

In deze repository staan op het moment van schrijven verschillende varianten van deze kaarten. Dit
zie je aan de bestandsnaam (e.g. `1e6`, `1e3`) –  maar natuurlijk ook aan de bestandsgrootte.

## CBS codes
Het CBS heeft voor elke regio een code. In de referentie tabel staat in welke regio elke gemeente
ligt. Daarnaast staan in deze tabel de codes van de gemeente in de andere indelingen
(e.g. gemeente, provincie, RPA, COROP).

Omdat de tabel dekkend is kan je hieruit ook afleiden welke gemeente in deze andere indelingen
vallen.

De referentie tabel hiervoor verschilt per jaar.
  * [Gebiedsindelingen 2015](http://statline.cbs.nl/StatWeb/publication/?VW=T&DM=SLNL&PA=82949NED&LA=NL) ([API](http://opendata.cbs.nl/ODataApi/OData/82949NED))


