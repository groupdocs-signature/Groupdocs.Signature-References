---
title: "pixel_aspect_ratio Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Seitenverhältnis der GIF‑Pixel."
type: docs
url: /de/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

Das Seitenverhältnis der GIF‑Pixel.

Pixel‑Seitenverhältnis – Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert dieses Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet:

Seitenverhältnis = (Pixel Aspect Ratio + 15) / 64

Das Pixel‑Seitenverhältnis ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64.

Werte:
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

### Siehe auch
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
