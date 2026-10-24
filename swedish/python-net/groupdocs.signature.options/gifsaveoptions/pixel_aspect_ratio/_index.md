---
title: "pixel_aspect_ratio egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "GIF-pixelns bildförhållande."
type: docs
url: /sv/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

GIF-pixelns bildförhållande.

Pixelaspektförhållande – faktor som används för att beräkna en approximation av pixelns bildförhållande i den ursprungliga bilden. Om värdet i fältet inte är 0 beräknas denna approximation av bildförhållandet enligt formeln:

Bildförhållande = (Pixelaspektförhållande + 15) / 64

Pixelaspektförhållandet definieras som kvoten av pixelns bredd över dess höjd. Värdeintervallet i detta fält tillåter specifikation av den bredaste pixeln 4:1 till den högsta pixeln 1:4 i steg om 1/64.

Värden:
- 0 – No aspect ratio information is given.
- 1..255 – Value used in the computation.

### Definition:
```python
@property
def pixel_aspect_ratio(self):
    ...
@pixel_aspect_ratio.setter
def pixel_aspect_ratio(self, value):
    ...
```

### Se även
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
