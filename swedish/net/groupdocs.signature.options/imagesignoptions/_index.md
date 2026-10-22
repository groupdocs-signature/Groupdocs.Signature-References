---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Representerar alternativen för bildsignatur."
type: docs
weight: 1670
url: /sv/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Representerar alternativen för bildsignatur.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Initierar en ny instans av ImageSignOptions‑klassen med standardvärden. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Initierar en ny instans av ImageSignOptions‑klassen med bildström. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Initierar en ny instans av ImageSignOptions‑klassen med bildfil. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Placera signatur på alla dokumentsidor. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Ange kantinställningar |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ange dokumenttypen för signaturalternativen [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer. Stöds uteslutande för digitala signaturer i PDF‑filer. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Höjd på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horisontell justering av signaturen på dokumentsidan. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Hämtar eller anger sökvägen till signaturens bildfil. Denna egenskap används endast om ImageStream inte är angiven. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Hämtar eller anger signaturens bildström. Om denna egenskap är angiven används den alltid istället för ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Vänster X‑position för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om horisontell justering inte är angiven). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för Left- och Top‑egenskaper. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Hämtar eller anger avståndet mellan signatur och dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är angiven). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Hämtar eller anger måtttypen (pixlar, procent eller millimeter) för marginal. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller anger dokumentsidans nummer för signering. Minimalt och standardvärde är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange vilka sidor som ska signeras. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rektangel för området där bilden ska placeras i dokumentet. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationsvinkel för signaturen på dokumentsidan (medurs). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definierar var formen ska visas i dokumentlayouten. Tillgänglig endast för Word‑dokument. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Hämta signaturtypen [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för Width- och Height‑egenskaper. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Stretch‑läge på dokumentsidan. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Övre Y‑position för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om vertikal justering inte är angiven). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Hämtar eller anger signaturens transparens (värde från 0,0 (opak) till 1,0 (genomskinlig)). Standardvärdet är 0 (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikal justering av signaturen på dokumentsidan. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Bredd på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Hämtar eller anger Z‑ordningspositionen för textsignaturen. Bestämmer visningsordningen för överlappande signaturer. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Skapar en ny instans av klassen ImageSignOptions med en fördefinierad bild från Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Rensar interna resurser |

### Anmärkningar

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Se även

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
