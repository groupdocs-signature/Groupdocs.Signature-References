---
title: "do_palette_correction Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Flag, das angibt, ob eine Palettenkorrektur angewendet wird."
type: docs
url: /de/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

Das Flag, das angibt, ob eine Palettenkorrektur angewendet wird.

Palette‑Korrektur bedeutet, dass jedes Mal, wenn ein Bild als GIF exportiert wird, die Farben des Quellbildes analysiert werden, um die am besten passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analysevorgang dauert etwas; das Ausgabebild wird jedoch die am besten passende Farbpalette besitzen und das Ergebnis ist visuell besser.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### Siehe auch
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
