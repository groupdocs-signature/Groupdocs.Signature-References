---
title: "color_resolution egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "GIF-färglösning."
type: docs
url: /sv/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

GIF-färglösning.

Färguppslagning - Antalet bitar per primärfärg som är tillgängliga i den ursprungliga bilden, minus 1. Detta värde representerar storleken på hela paletten som färgerna i grafiken valdes från, inte antalet färger som faktiskt används i grafiken. Till exempel, om värdet i detta fält är 3, hade paletten för den ursprungliga bilden 4 bitar per primärfärg tillgängliga för att skapa bilden. Detta värde bör anges för att indikera rikedom i den ursprungliga paletten, även om inte varje färg från hela paletten är tillgänglig på källmaskinen.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Se även
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
