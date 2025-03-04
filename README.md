# Claeissens-copy of the Map of the Liberty of Bruges

This repository contains static level 0 [IIIF Image API](https://iiif.io/api/image/2.0/) tiles of the 1597 copy by Pieter Claeissens of the 1571 *Map of the Liberty of Bruges* (*Kaart van het Brugse Vrije*) by Pieter Pourbus. The map is available in the collection of [Musea Brugge](https://collectie.museabrugge.be/collection/work/id/0000_GRO0438_I), including a [IIIF Manifest](https://dam.museabrugge.be/iiif/3/18761/manifest.json) pointing to a Cantaloupe server managed by the museum and [meemoo](https://meemoo.be/). The tiles and manifest in this repository serve as a backup for a [Mapathon](https://mappingpourbus.ugent.be/) workshop organised on March 14th and 15th 2025.

Links to view and annotate the map:

- [IIIF Presentation Manifest](https://manuelclaeysbouuaert.be/claeissens/manifest.json)
- [Open in Allmaps Editor](https://editor.allmaps.org/#/collection?url=https://manuelclaeysbouuaert.be/claeissens/manifest.json)
- [Open in Allmaps Viewer](https://viewer.allmaps.org/?url=https://manuelclaeysbouuaert.be/claeissens/manifest.json)
- [Open in Theseus Viewer](https://theseus-viewer.netlify.app/?iiif-content=https://manuelclaeysbouuaert.be/claeissens/manifest.json)

Technical information about the map:

The original digitalisation resulted in a picture of 158174 x 95614 pixels. This has been scaled down to a lower resolution to find a better balance between detail and manageability.

---

The tiles were made with [Sharp](https://sharp.pixelplumbing.com/) using [these scripts](https://github.com/sammeltassen/iiif-tiler). The IIIF Presentation Manifest was made using [this Notebook](https://observablehq.com/d/46eb57ecfeded102).

A custom 'starting' Georeference Annotation page was made with [this Notebook](https://observablehq.com/d/b7ae55c7ab37313b).