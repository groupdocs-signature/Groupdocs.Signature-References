---
title: "pixel_aspect_ratio eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De GIF-pixelaspectverhouding."
type: docs
url: /nl/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

De GIF-pixelaspectverhouding.

Pixel Aspect Ratio – factor die wordt gebruikt om een benadering van de beeldverhouding van de pixel in de originele afbeelding te berekenen. Als de waarde van het veld niet 0 is, wordt deze benadering van de beeldverhouding berekend op basis van de formule:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

De Pixel Aspect Ratio wordt gedefinieerd als het quotiënt van de breedte van de pixel gedeeld door zijn hoogte. Het waardebereik in dit veld maakt specificatie mogelijk van de breedste pixel van 4:1 tot de hoogste pixel van 1:4 in stappen van 1/64.

Waarden:
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

### Zie ook
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
