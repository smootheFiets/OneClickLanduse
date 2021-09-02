# OneClickLanduse
Quick JOSM presets that work with a single click. Inspired by OneClick, adapted for refinement of landuse tagging in the Netherlands.

Landuse mapping in the Netherlands relies heavily on an import from 3dShapes, which in turn is based on data taken around 2008.  https://wiki.openstreetmap.org/wiki/3dShapes
As of 2021, much of it is outdated.  Also, there are undesirable idiosyncrasies, e.g., most landuse=grass should be landuse=meadow.  Also, grass/farmland polygons tend to include backyards of residential homes, which are, of course, covered in plants but should be part of residential.

This preset provides simple presets that set landuse to the appropriate value and delete the source tag (typically: source=3dShapes).  Preset names are in German because that's a) easier on the author and b) different from existing preset names in English (so they're quick and easy to find after pressing F3).  I'll be happy to accomodate other users, should they be interested.  Let me know!

Presets contained:
* Acker: landuse=farmland
* Weide: landuse=meadow
* Bauernhof: landuse=farmyard
* Wohngebiet: landuse=residential

## Version history
* 0.1_2021_09_02: initial commit

