---
title: ColorResolution
second_title: GroupDocs.Signature voor .NET API-referentie
description: Krijgt of stelt de GIFkleurresolutie in.
type: docs
weight: 30
url: /nl/net/groupdocs.signature.options/gifsaveoptions/colorresolution/
---
## GifSaveOptions.ColorResolution property

Krijgt of stelt de GIF-kleurresolutie in.

```csharp
public byte ColorResolution { get; set; }
```

### Opmerkingen

Kleurresolutie - Aantal bits per primaire kleur dat beschikbaar is voor de originele afbeelding, min 1. Deze waarde vertegenwoordigt de grootte van het volledige palet van waaruit de kleuren in de afbeelding zijn geselecteerd, niet het aantal kleuren dat daadwerkelijk in de afbeelding is gebruikt. Als de waarde in dit veld bijvoorbeeld 3 is, dan had het palet van de originele afbeelding 4 bits per primaire kleur beschikbaar om de afbeelding te maken. Deze waarde moet worden ingesteld om de rijkdom van het originele palet aan te geven, zelfs als niet elke kleur van het hele palet beschikbaar is op de bronmachine.

### Zie ook

* class [GifSaveOptions](../../gifsaveoptions)
* naamruimte [GroupDocs.Signature.Options](../../gifsaveoptions)
* montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->