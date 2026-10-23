---
title: "color_resolution Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die GIF‑Farbauflösung."
type: docs
url: /de/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

Die GIF‑Farbauflösung.

Farbauflösung – Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben im Bild ausgewählt wurden, nicht die Anzahl der tatsächlich im Bild verwendeten Farben. Zum Beispiel, wenn der Wert in diesem Feld 3 ist, dann hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Erstellung des Bildes. Dieser Wert sollte gesetzt werden, um die Reichhaltigkeit der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe der gesamten Palette auf der Quellmaschine verfügbar ist.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Siehe auch
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
