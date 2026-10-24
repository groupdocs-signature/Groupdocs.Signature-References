---
title: "do_palette_correction egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som indikerar om palettkorrigering tillämpas."
type: docs
url: /sv/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

Flaggan som indikerar om palettkorrigering tillämpas.

Palettkorrigering innebär att när en bild exporteras till GIF analyseras källbildens färger för att bygga den bäst matchande paletten (om bildpaletten inte finns eller inte specificeras i alternativen). Analysprocessen tar lite tid; dock kommer den exporterade bilden att ha den bäst matchande färgpaletten och resultatet blir visuellt bättre.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### Se även
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
