---
title: TextSignOptions
second_title: GroupDocs.Signature för .NET API-referens
description: Representerar textsignaturalternativen.
type: docs
weight: 1730
url: /sv/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Representerar textsignaturalternativen.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | Initierar en ny instans av klassen TextSignOptions med standardvärden. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | Initierar en ny instans av klassen TextSignOptions med text. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Sätt signatur på alla dokumentsidor. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Hämtar eller ställer in signaturbakgrundsinställningarna. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Ange kantinställningar |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ställ in dokumenttyp för signaturalternativ[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Hämtar eller ställer in teckensnitt för signatur. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Hämtar eller ställer in signaturens framfärg. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Hämtar eller ställer in titeln på textformulärfältet för att lägga in textsignatur i det. Den här egenskapen kunde endast användas med SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Hämtar eller ställer in typen av formulärfält för att lägga in textsignatur i det. Den här egenskapen kunde endast användas med SignatureImplementation = TextToFormField. Värdet som standard är AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Signaturhöjd på dokumentsida i måtten värden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType-egenskap). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horisontell justering av signatur på dokumentsidan. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Vänster X-position för signatur på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) Egenskapen LocationMeasureType). (fungerar om horisontell justering inte anges). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för egenskaper för vänster och topp. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Hämtar eller ställer in avståndet mellan Sign- och Dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är specificerad). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Hämtar eller ställer in måtttypen (pixlar, procent eller millimeter) för Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Hämtar eller ställer in det ursprungliga attributet. Om det är inställt kan dokumentspecifika signaturer användas. Inbyggd textvattenstämpel för WordProcessing-dokument skiljer sig till exempel från vanliga. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller ställer in dokumentets sidnummer för signering. Minimalt och standardvärdet är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange sidor som ska signeras. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotationsvinkel för signatur på dokumentsidan (medurs). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Hämtar eller ställer in typen av form för att lägga text. Den här egenskapen kunde endast användas med SignatureImplementation = TextStamp. Värdet är som standard Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Hämtar eller ställer in signaturens unika ID. Det kan användas i signaturverifieringsalternativ. Egenskapen stöds endast för PDF-dokument. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Hämtar eller ställer in typen av textsignaturimplementering. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Hämta signaturtypen[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Mättyp (pixlar, procent eller millimeter) för egenskaperna Bredd och Höjd. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Stretch-läge på dokumentsidan. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Hämtar eller ställer in signaturtexten. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Horisontell justering av text inuti en signatur. Den här funktionen stöds endast för implementeringar av bild- och anteckningssignatur (se[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation-egenskap). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Vertikal justering av text inuti en signatur. Den här funktionen stöds endast för implementering av bildsignatur (se[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation-egenskap). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Överst Y Position för signatur på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype)Egenskapen LocationMeasureType). (fungerar om vertikal justering inte anges). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Hämtar eller ställer in signaturtransparensen (värde från 0,0 (opak) till 1,0 (rensar)). Standardvärdet är 0 (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Vertikal justering av signatur på dokumentsidan. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Signaturens bredd på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType-egenskap). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Hämtar eller ställer in Z-ordningens position för textsignatur. Bestämmer visningsordningen för överlappande signaturer. |

### Anmärkningar

**Läs mer**

* Grundläggande användning av att skapa elektronisk textsignatur av GroupDocs.Signatur: [Hur man e-signerar dokument med textsignatur](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Avancerad användning av inställningar för text elektronisk signatur med GroupDocs.Signatur: [Avancerad användning för eSign-dokument med textsignatur och ytterligare inställningar](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Se även

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namnutrymme [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
