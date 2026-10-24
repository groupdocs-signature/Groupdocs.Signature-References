---
title: "color_resolution eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De GIF-kleuroplossing."
type: docs
url: /nl/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

De GIF-kleuroplossing.

Color Resolution - Aantal bits per primaire kleur beschikbaar in de originele afbeelding, min 1. Deze waarde vertegenwoordigt de grootte van de volledige palet waaruit de kleuren in de afbeelding zijn geselecteerd, niet het aantal kleuren dat daadwerkelijk in de afbeelding wordt gebruikt. Bijvoorbeeld, als de waarde in dit veld 3 is, dan had het palet van de originele afbeelding 4 bits per primaire kleur beschikbaar om de afbeelding te maken. Deze waarde moet worden ingesteld om de rijkdom van het originele palet aan te geven, zelfs als niet elke kleur uit het volledige palet beschikbaar is op de bronmachine.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Zie ook
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
