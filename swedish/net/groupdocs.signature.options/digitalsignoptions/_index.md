---
title: DigitalSignOptions
second_title: GroupDocs.Signature för .NET API-referens
description: Representerar alternativen för digital signatur.
type: docs
weight: 1260
url: /sv/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Representerar alternativen för digital signatur.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initierar en ny instans av klassen DigitalSignOptions med standardvärden. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildström. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildfil. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildström. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildfil. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Sätt signatur på alla dokumentsidor. Den här egenskapen kan endast användas för bildformat med flera ramar (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Ange kantinställningar |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Hämtar eller ställer in sökvägen till den digitala certifikatfilen. Den här egenskapen används endast om CertificateStream inte anges. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Hämtar eller ställer in digital certifikatström. Om den här egenskapen anges används den alltid istället CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Hämtar eller ställer in signaturkontakten. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ställ in dokumenttyp för signaturalternativ[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Signaturhöjd på dokumentsida i måtten värden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horisontell justering av signatur på dokumentsidan. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Hämtar eller ställer in sökvägen för signaturbildsfilen. Den här egenskapen används endast om ImageStream inte anges. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Hämtar eller ställer in signaturbildströmmen. Om den här egenskapen anges används den alltid istället ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Vänster X-position för signatur på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om horisontell justering inte anges). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Hämtar eller ställer in signaturplatsen. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för egenskaper för vänster och topp. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Hämtar eller ställer in avståndet mellan Sign- och Dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är specificerad). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Hämtar eller ställer in måtttypen (pixlar, procent eller millimeter) för Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller ställer in dokumentets sidnummer för signering. Minimalt och standardvärdet är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange sidor som ska signeras. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Hämtar eller ställer in lösenordet för digitalt certifikat. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Hämtar eller ställer in orsaken till signaturen. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rektangel av området för att placera bilden på dokumentet. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationsvinkel för signatur på dokumentsidan (medurs). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Hämtar eller ställer in egenskaper för dokumentets digitala signatur. För att signera PDF-dokument är det möjligt att ställa in avancerade egenskaper genom att använda instans av[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Hämta signaturtypen[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Mättyp (pixlar, procent eller millimeter) för egenskaperna Bredd och Höjd. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Stretch-läge på dokumentsidan. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Överst Y Position för signatur på dokumentsidan i Mätvärden (pixlar, procent eller millimeter se[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om vertikal justering inte anges). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Hämtar eller ställer in signaturtransparensen (värde från 0,0 (opak) till 1,0 (rensar)). Standardvärdet är 0 (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikal justering av signatur på dokumentsidan. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Hämtar eller ställer in signaturens synlighet. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Signaturens bredd på dokumentsidan i Mätvärden (pixlar, procent eller millimeter[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES-typ[`XAdESType`](./xadestype) . Standardvärdet är Inget (XAdES är avstängt). För närvarande stöds XAdES-signaturtypen endast för kalkylarksdokument. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Hämtar eller ställer in Z-ordningens position för textsignatur. Bestämmer visningsordningen för överlappande signaturer. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Rensar interna resurser |

### Anmärkningar

**Läs mer**

* Grundläggande användning för att skapa digital elektronisk signatur av GroupDocs.Signatur: [Hur man e-signerar dokument med digital signatur](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Avancerad användning av inställningar för digital elektronisk signatur med GroupDocs.Signatur: [Avancerad användning för eSign-dokument med digital signatur och ytterligare inställningar](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Se även

* class [ImageSignOptions](../imagesignoptions)
* namnutrymme [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
