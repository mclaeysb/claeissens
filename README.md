# Claeissens-copy of the Map of the Liberty of Bruges

This repository contains static level 0 [IIIF Image API](https://iiif.io/api/image/2.0/) images of the 1597 copy by Pieter Claeissens of the 1571 *Map of the Liberty of Bruges* (*Kaart van het Brugse Vrije*) by Pieter Pourbus. The map is available in the collection of [Musea Brugge](https://collectie.museabrugge.be/collection/work/id/0000_GRO0438_I), including a [IIIF Manifest](https://dam.museabrugge.be/iiif/3/18761/manifest.json) pointing to a Cantaloupe server managed by the museum and [meemoo](https://meemoo.be/). The images and manifest in this repository serve as a backup for a [Mapathon](https://mappingpourbus.ugent.be/) workshop organised on March 14th and 15th 2025.

The original digitalisation resulted in a picture of 158174 x 95614 pixels. This has been scaled down to a lower resolution of 52724 x 31871 to find a better balance between detail and manageability.

Two manifests are available:

- `manifest.json` uses the images in the `img/` directory and is the manifest wih one canvas of the entire image.
- `tiled-manifest.json` uses the images in the `tiled-img/` directory and is a manifest with a canvas for each of the 114 cut-outs (confusingly called 'tiles' or 'tegels') that will be assigned to participants during the Mapathon. Every 'tegel' is also tiled (in the *IIIF-sense*).

Links to view and annotate the `manifest.json`:

- [IIIF Presentation Manifest](https://manuelclaeysbouuaert.be/claeissens/manifest.json)
- [Open in Allmaps Editor](https://editor.allmaps.org/#/collection?url=https://manuelclaeysbouuaert.be/claeissens/manifest.json)
- [Open in Allmaps Viewer](https://viewer.allmaps.org/?url=https://manuelclaeysbouuaert.be/claeissens/manifest.json)
- [Open in Theseus Viewer](https://theseus-viewer.netlify.app/?iiif-content=https://manuelclaeysbouuaert.be/claeissens/manifest.json)

Links to view and annotate the `tiled-manifest.json`:

- [IIIF Presentation Manifest](https://manuelclaeysbouuaert.be/claeissens/tiled-manifest.json)
- [Open in Allmaps Editor](https://editor.allmaps.org/#/collection?url=https://manuelclaeysbouuaert.be/claeissens/tiled-manifest.json)
- [Open in Allmaps Viewer](https://viewer.allmaps.org/?url=https://manuelclaeysbouuaert.be/claeissens/tiled-manifest.json)
- [Open in Theseus Viewer](https://theseus-viewer.netlify.app/?iiif-content=https://manuelclaeysbouuaert.be/claeissens/tiled-manifest.json)

---

The tiles of the `manifest.json` were made with [Sharp](https://sharp.pixelplumbing.com/) using [these scripts](https://github.com/sammeltassen/iiif-tiler) (and a `height` parameter was added to the `info.json` file manually). The IIIF Presentation Manifest was made using [this Notebook](https://observablehq.com/d/46eb57ecfeded102).

A custom 'starting' Georeference Annotation page was made with [this Notebook](https://observablehq.com/d/b7ae55c7ab37313b).

The tiles of the `tiled-manifest.json` were made using an adapted version of `iiif-tiler`. The Manifest and 'starting' Georeference annotation were made in the same notebook.