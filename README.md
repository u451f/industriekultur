# industriekultur

This is machine readable map data for old factory buildings in Leipzig.
There are other entities making maps of industrial culture in Leipzig,
but either they use GoogleMaps (Industriekultur Leipzig e.V.) and map
only places that still exist in some form, or they just have lists of
places during a certain epoch (Military Airfields) or they concentrate
only on one area (Lindenauer Stadtteilverein). Nobody has machine
readable data.

## Scope

For now, I'm only interested in mapping factories. Breweries and large
scale food production can be part of this map.

I'm not interested (yet) in mapping other industrial architecture (gas
factories, gasometers, train lines, train supply tracks, etc.). However,
one could imagine creating a second geoJSON file for those. Especially
the (now removed) train supply tracks might be super interesting to map
in the case of Leipzig.

## Goal

My goal is to

* have machine readable data: I use geoJSON for that,
* also map places that are entirely gone
* have an entry for what happened to these places during World War II
  (field in geoJSON called "WWII") and after the German reunification
  (field in geoJSON called "Nachwende")

## Contribute

Feel free to make suggestions about the JSON scheme and to contribute
data!

* fork Git repo
* create branch
* commit your modifications to your fork
* create a pull request

## Future plans

* I also would like to map the factory canteens or restaurants in
  industrial places that are in service today (for now I only know about
  Kirow, Tapetenwerk, Niemeyer Sphere).
* I want to use different marker colors and shapes:
  - green: factory still producing at the same place
  - lightblue: factory still producing but at different location
  - darkblue: building still exists, but with different usage (field
    "Nutzung"
  - purple: building does not exist anymore
  - orange: factory canteens and restaurants
* I want to create a printed map. (Actually, this is my first goal, but
  I thought: why not create this map from a digital file so that others
  can contribute and the data be reused?)
* One could imagine some walks around the neighborhoods using this map.

## Data sources

* [Häuserliste Lindenauer
  Stadtteilverein](https://www.lindenauerstadtteilverein.de/heimatkunde/haeuserliste.htm)
* [Volkseigene Betriebe und Kombinat in der DDR](https://www.mil-airfields.de/ddr/orte/leipzig.html)
* Katalog [Industriekultur Leipzig e.V.](http://www.leipziger-industriekultur.de/category/objekte/)
* [Staatsarchiv Sachsen](https://www.archiv.sachsen.de/archiv/bestand.jsp?oid=09.&bestandid=&_ptabs=%7B%22%23tab-einleitung%22%3A1%7D&syg_id=&_cp=%7B%22accordion-bestaendenavigation%22%3A%7B%220%22%3Atrue%7D%2C%22previousOpen%22%3A%7B%22group%22%3A%22accordion-bestaendenavigation%22%2C%22idx%22%3A0%7D%7D#einleitung) → Unter Punkt 9 Wirtschaft finden sich Wirtschaftszweige
* [Leipzig Lexikon](https://www.leipzig-lexikon.de/)
* Wikipedia
* People I meet

## Random thoughts

### Reading an urban landscape

To really deeply understand a place, in that case: an urban environment,
it seems useful to be able to [read the
landscape](https://www.williamcronon.net/researching/landscapes.htm).
In the case of Leipzig, some things that one can note are those:

- Some addresses where buildings disappeared entirely, or big parks have
  been built are actually places that were hit by bombs during World War
  II (in the east of the city this is quite common) or that were hosting
  factories until the end of the GDR which have been torn down (eg
  Jahrtausendfeld in Lindenau).

- The same is true for street numbers that don't exist anymore (eg.
  Eisenbahnstrasse 70). So when you cannot find a street number of an
  old factory address, look at the surrounding numbers. Also check if a
  street has been renamed. [There is an index of all street names and
  their older
  names](https://www.leipzig.de/buergerservice-und-verwaltung/unsere-stadt/gebietsgliederung-und-strassennamen/strassennamen/).

- Factory buildings were either really big factories (like in Plagwitz)
  or smaller ones in backyards (eg Luppenstrasse 24). Therefore, when
  mapping those places, it might not be sufficient to map the street
  address, but one would actually need to verify which building was the
  factory building. This works reasonably well on
  [OpenStreetMap](https://osm.org), which has details of buildings.

## License

I don't know yet. Some information on this map comes from other places
and I first need to check which of this information can be reused at
all.
