---
title: BarcodeSignOptions
second_title: GroupDocs.Signature för .NET API-referens
description: Representerar streckkodssignaturalternativen.
type: docs
weight: 1260
url: /sv/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Representerar streckkodssignaturalternativen.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Initierar en ny instans av klassen BarcodeSignOptions med standardvärden. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | Initierar en ny instans av klassen BarcodeSignOptions med text. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | Initierar en ny instans av klassen BarcodeSignOptions med text. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Sätt signatur på alla dokumentsidor. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Hämtar eller ställer in signaturbakgrundsinställningarna. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Ange kantinställningar |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Hämtar eller ställer in justeringen av text i resultatet streckkodsbild. Standardvärdet är None. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ställ in dokumenttyp för signaturalternativ[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Hämtar eller ställer in streckkodstyp. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Hämtar eller ställer in teckensnitt för signatur. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Hämtar eller ställer in framfärgen för streckkodsstreck Användning av den här egenskapen kan orsaka problem med verifieringen. Använd den försiktigt. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Hämtar eller ställer in titeln på textformulärfältet för att lägga in textsignatur i det. Den här egenskapen kunde endast användas med SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Hämtar eller ställer in typen av formulärfält för att lägga in textsignatur i det. Den här egenskapen kunde endast användas med SignatureImplementation = TextToFormField. Värdet som standard är AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Signaturhöjd på dokumentsida i måtten värden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType-egenskap). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horisontell justering av signatur på dokumentsidan. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Hämtar eller ställer in utrymmet mellan streckkodselement och resultatbildskanter. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Vänster X-position för signatur på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) Egenskapen LocationMeasureType). (fungerar om horisontell justering inte anges). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för egenskaper för vänster och topp. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Hämtar eller ställer in avståndet mellan Sign- och Dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är specificerad). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Hämtar eller ställer in måtttypen (pixlar, procent eller millimeter) för Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Hämtar eller ställer in det ursprungliga attributet. Om det är inställt kan dokumentspecifika signaturer användas. Inbyggd textvattenstämpel för WordProcessing-dokument skiljer sig till exempel från vanliga. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller ställer in dokumentets sidnummer för signering. Minimalt och standardvärdet är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange sidor som ska signeras. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Hämtar eller ställer in flagga för att hämta streckkodsbildinnehåll för en signatur som placerades på dokumentsidan. Om denna flagga är inställd på sann, kommer innehållet i streckkodsignaturbilden att behålla rå bilddata enligt önskat format[`ReturnContentType`](./returncontenttype) . Som standard är detta alternativ inaktiverat. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | Anger filtyp för returnerat bildinnehåll i streckkodssignaturen när ReturnContent-egenskapen är aktiverad. Som standard är den inställd på Null. Det innebär att returnera streckkodsbildinnehåll i originalformat. Detta bildformat anges på[`Format`](../../groupdocs.signature.domain/barcodesignature/format) Möjliga värden som stöds är: FileType.JPEG, FileType.PNG, FileType.BMP. Om det angivna formatet inte stöds kommer streckkodsbildinnehåll i .png-format att returneras. |
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

* Grundläggande användning för att skapa elektronisk streckkodsignatur av GroupDocs.Signatur: [Hur man e-signerar dokument med streckkodsignatur](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Avancerad användning av inställningar för streckkods elektronisk signatur med GroupDocs.Signatur: [Avancerad användning för eSign-dokument med streckkodssignatur och ytterligare inställningar](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Se även

* class [TextSignOptions](../textsignoptions)
* namnutrymme [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
