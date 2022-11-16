---
title: ImageSignOptions
second_title: GroupDocs.Signature för .NET API-referens
description: Representerar bildsignaturalternativen.
type: docs
weight: 1340
url: /sv/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Representerar bildsignaturalternativen.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Initierar en ny instans av klassen ImageSignOptions med standardvärden. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Initierar en ny instans av klassen ImageSignOptions med bildström. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Initierar en ny instans av klassen ImageSignOptions med bildfil. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Sätt signatur på alla dokumentsidor. Den här egenskapen kan endast användas för bildformat med flera ramar (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Ange kantinställningar |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ställ in dokumenttyp för signaturalternativ[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Signaturhöjd på dokumentsida i måtten värden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horisontell justering av signatur på dokumentsidan. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Hämtar eller ställer in sökvägen för signaturbildsfilen. Den här egenskapen används endast om ImageStream inte anges. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Hämtar eller ställer in signaturbildströmmen. Om den här egenskapen anges används den alltid istället ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Vänster X-position för signatur på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om horisontell justering inte anges). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för egenskaper för vänster och topp. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Hämtar eller ställer in avståndet mellan Sign- och Dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är specificerad). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Hämtar eller ställer in måtttypen (pixlar, procent eller millimeter) för Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller ställer in dokumentets sidnummer för signering. Minimalt och standardvärdet är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange sidor som ska signeras. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rektangel av området för att placera bilden på dokumentet. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationsvinkel för signatur på dokumentsidan (medurs). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Hämta signaturtypen[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Mättyp (pixlar, procent eller millimeter) för egenskaperna Bredd och Höjd. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Stretch-läge på dokumentsidan. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Överst Y Position för signatur på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om vertikal justering inte anges). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Hämtar eller ställer in signaturtransparensen (värde från 0,0 (opak) till 1,0 (rensar)). Standardvärdet är 0 (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikal justering av signatur på dokumentsidan. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Signaturens bredd på dokumentsidan i Mätvärden (pixlar, procent eller millimeter[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Hämtar eller ställer in Z-ordningens position för textsignatur. Bestämmer visningsordningen för överlappande signaturer. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Skapar en ny instans av klassen ImageSignOptions med fördefinierad bild från Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Rensar interna resurser |

### Anmärkningar

**Läs mer**

* Grundläggande användning av att skapa elektroniska bildsignaturer av GroupDocs.Signatur: [Hur man e-signerar dokument med bildsignatur](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Avancerad användning av inställningar för bild elektronisk signatur med GroupDocs.Signatur: [Avancerad användning för eSign-dokument med bildsignatur och ytterligare inställningar](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Se även

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namnutrymme [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
