---
title: "proprietà pixel_aspect_ratio"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il rapporto di aspetto dei pixel GIF."
type: docs
url: /it/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

Il rapporto di aspetto dei pixel GIF.

Pixel Aspect Ratio – fattore utilizzato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto viene calcolata in base alla formula:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza del pixel e la sua altezza. L'intervallo di valori in questo campo consente di specificare il pixel più largo di 4:1 fino al pixel più alto di 1:4 in incrementi di 1/64.

Valori:
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

### Vedi anche
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
