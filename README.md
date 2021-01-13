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
* I want to create a printable map from this.
* One could imagine some walks around the neighborhoods using this map.
