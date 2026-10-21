---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Stelt de beeldhandtekeningopties voor."
type: docs
weight: 1670
url: /nl/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Stelt de beeldhandtekeningopties voor.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met standaardwaarden. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met een afbeeldingstroom. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Initialiseert een nieuw exemplaar van de ImageSignOptions-klasse met een afbeeldingsbestand. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Plaats handtekening op alle documentpagina's. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aanvullende handtekeningweergave. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specificeer randinstellingen |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Haalt het documenttype van de handtekeningopties op of stelt het in [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Handtekeningextensies. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Haalt het hash-algoritme op dat moet worden gebruikt voor cryptografische bewerkingen, of stelt dit in. Alleen ondersteund voor digitale handtekeningen in PDF-bestanden. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Hoogte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontale uitlijning van de handtekening op de documentpagina. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Geeft of stelt het bestandspad van de handtekeningafbeelding in. Deze eigenschap wordt alleen gebruikt als ImageStream niet is gespecificeerd. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Geeft of stelt de handtekeningafbeeldingsstroom in. Als deze eigenschap is gespecificeerd, wordt deze altijd gebruikt in plaats van ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Linker X-positie van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (werkt als horizontale uitlijning niet is gespecificeerd). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Links en Boven. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Geeft of stelt de ruimte tussen handtekening en documentranden in. (werkt ALLEEN als horizontale of verticale uitlijning is gespecificeerd). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Geeft of stelt het meettype (pixels, procenten of millimeters) voor marge in. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Geeft of stelt het paginanummer van het document voor ondertekening in. Minimale en standaardwaarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opties om pagina's op te geven die ondertekend moeten worden. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rechthoek van het gebied waarin de afbeelding op het document wordt geplaatst. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotatiehoek van de handtekening op de documentpagina (met de klok mee). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definieert waar de vorm moet worden gepresenteerd in de documentlay-out. Alleen beschikbaar voor Word-documenten. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Haal het handtekeningtype op [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Rekmodus op Documentpagina. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (werkt als verticale uitlijning niet is gespecificeerd). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Geeft of stelt de transparantie van de handtekening in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). Standaardwaarde is 0 (ondoorzichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Verticale uitlijning van de handtekening op de documentpagina. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Breedte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Geeft of stelt de Z-order positie van de teksthandtekening in. Bepaalt de weergavevolgorde van overlappende handtekeningen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Maakt een nieuw exemplaar van de ImageSignOptions-klasse met een vooraf gedefinieerde afbeelding uit Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Wis interne bronnen |

### Opmerkingen

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Zie ook

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
