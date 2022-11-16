---
title: BarcodeSearchOptions
second_title: GroupDocs.Signature för .NET API-referens
description: Representerar sökalternativ för streckkodssignaturer.
type: docs
weight: 1180
url: /sv/net/groupdocs.signature.options/barcodesearchoptions/
---
## BarcodeSearchOptions class

Representerar sökalternativ för streckkodssignaturer.

```csharp
public class BarcodeSearchOptions : SearchOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BarcodeSearchOptions](barcodesearchoptions#constructor)() | Initierar en ny instans av klassen BarcodeSearchOptions med standardvärden. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_1)(BarcodeType) | Initierar en ny instans av klassen BarcodeSearchOptions med kodningstypvärde. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_2)(BarcodeType, string) | Initierar en ny instans av klassen BarcodeSearchOptions med kodningstyp och textvärden. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flagga för att söka på varje dokumentsida. Som standard är detta värde satt till true. |
| [EncodeType](../../groupdocs.signature.options/barcodesearchoptions/encodetype) { get; set; } | Anger Encode Type-egenskap för att söka efter streckkoder. Om detta värde inte är inställt, bearbetas sökningen för alla stödda streckkodstyper |
| [MatchType](../../groupdocs.signature.options/barcodesearchoptions/matchtype) { get; set; } | Hämtar eller ställer in streckkodstext Sök efter matchningstyp. Den används endast när egenskapen Text är inställd. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Hämtar eller ställer in dokumentets sidnummer för sökning. Värdet är valfritt. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Alternativ för att ange sidor för signatursökning. |
| [ReturnContent](../../groupdocs.signature.options/barcodesearchoptions/returncontent) { get; set; } | Hämtar eller ställer in flaggan för att ta tag i streckkodsbildinnehållet i signaturen på dokumentsidan. Om denna flagga är inställd på sann, kommer innehållet i streckkodsignaturbilden att behålla rå bilddata enligt önskat format[`ReturnContentType`](./returncontenttype) . Som standard är detta alternativ inaktiverat. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesearchoptions/returncontenttype) { get; set; } | Anger filtyp för returnerat bildinnehåll i streckkodssignaturen när ReturnContent-egenskapen är aktiverad. Som standard är den inställd på Null. Det innebär att returnera streckkodsbildinnehåll i originalformat. Detta bildformat anges på[`Format`](../../groupdocs.signature.domain/barcodesignature/format) Möjliga värden som stöds är: FileType.JPEG, FileType.PNG, FileType.BMP. Om det angivna formatet inte stöds kommer streckkodsbildinnehåll i .png-format att returneras. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flagga för att endast returnera signaturer markerade som IsSignature. Som standard är värdet false som indikerar att returnera alla signaturer som matchar angivna kriterier. |
| [Text](../../groupdocs.signature.options/barcodesearchoptions/text) { get; set; } | Anger streckkodsignaturtext om den ska sökas och matchas. |

### Anmärkningar

**Läs mer**

* Grundläggande användning av sökning efter elektronisk streckkodsignatur av GroupDocs.Signatur: [ Hur man eSearch streckkodsignaturer i ett dokument](https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures)
* Avancerad användning av inställningar för sökning efter elektronisk streckkodsignatur med GroupDocs.Signatur: [Avancerad användning av eSearch-streckkodsignaturer i ett dokument och ytterligare inställningar](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures)

### Se även

* class [SearchOptions](../searchoptions)
* namnutrymme [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->