---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Representerar alternativen för streckkodssignatur."
type: docs
weight: 1450
url: /sv/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Representerar alternativen för streckkodssignatur.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Initierar en ny instans av klassen BarcodeSignOptions med standardvärden. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | Initierar en ny instans av klassen BarcodeSignOptions med text. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | Initierar en ny instans av klassen BarcodeSignOptions med text. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Placera signatur på alla dokumentsidor. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Hämtar eller anger bakgrundsinställningarna för signaturen. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Ange kantinställningar |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Hämtar eller anger justeringen av text i den resulterande streckkodbilden. Standardvärdet är None. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ange dokumenttypen för signaturalternativen [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Hämtar eller anger streckkodstyp. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Hämtar eller anger teckensnittet för signaturen. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Hämtar eller anger förgrundsfärgen för streckkodsbalkar. Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Hämtar eller anger titeln på textformulärfältet för att placera textsignatur i det. Denna egenskap kan endast användas med SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Hämtar eller anger typen av formulärfält för att placera textsignatur i det. Denna egenskap kan endast användas med SignatureImplementation = TextToFormField. Standardvärdet är AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer. Stöds uteslutande för digitala signaturer i PDF‑filer. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Höjd på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType‑egenskapen). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horisontell justering av signaturen på dokumentsidan. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Hämtar eller anger avståndet mellan streckkodselement och resultatbildens kanter. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Vänster X‑position för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType‑egenskapen). (fungerar om horisontell justering inte är specificerad). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för Left- och Top‑egenskaper. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Hämtar eller anger avståndet mellan signatur och dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är angiven). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Hämtar eller anger måtttypen (pixlar, procent eller millimeter) för marginal. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Hämtar eller anger den inhemska attributen. Om den är angiven kan dokumentspecifika signaturer användas. Inbyggt textvattenmärke för WordProcessing‑dokument är till exempel annorlunda än vanliga. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller anger dokumentsidans nummer för signering. Minimalt och standardvärde är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange vilka sidor som ska signeras. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Hämtar eller anger flaggan för att hämta streckkodsbildens innehåll för en signatur som placerats på dokumentsidan. Om denna flagga är satt till true behåller streckkodssignaturens bildinnehåll rå bilddata i det erforderliga formatet [`ReturnContentType`](./returncontenttype). Som standard är detta alternativ inaktiverat. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | Anger filtypen för det returnerade bildinnehållet för streckkodssignaturen när ReturnContent‑egenskapen är aktiverad. Som standard är den satt till Null. Det innebär att streckkodsbildens innehåll returneras i originalformat. Detta bildformat anges i [`Format`](../../groupdocs.signature.domain/barcodesignature/format). Möjliga stödjade värden är: FileType.JPEG, FileType.PNG, FileType.BMP. Om angivet format inte stöds returneras streckkodsbildens innehåll i .png‑format. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotationsvinkel för signaturen på dokumentsidan (medurs). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Definierar var formen ska visas i dokumentlayouten. Tillgänglig endast för Word‑dokument. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Hämtar eller anger typen av form för att placera text. Denna egenskap kan endast användas med SignatureImplementation = TextStamp. Standardvärdet är Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Hämtar eller anger den unika ID‑n för signaturen. Den kan användas i alternativ för signaturverifiering. Egenskapen stöds endast för Pdf‑dokument. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Hämtar eller anger typen av textsignaturimplementation. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Hämta signaturtypen [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för Width- och Height‑egenskaper. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Stretch‑läge på dokumentsidan. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Hämtar eller anger signaturens text. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Horisontell justering av text inom en signatur. Denna funktion stöds endast för Image‑ och Annotation‑signaturimplementationer (se [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation‑egenskapen). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Vertikal justering av text inom en signatur. Denna funktion stöds endast för Image‑signaturimplementation (se [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation‑egenskapen). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Övre Y‑position för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType‑egenskapen). (fungerar om vertikal justering inte är specificerad). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Hämtar eller anger signaturens transparens (värde från 0,0 (opak) till 1,0 (genomskinlig)). Standardvärdet är 0 (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Vertikal justering av signaturen på dokumentsidan. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Bredd på signatur på dokumentsida i mätenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType‑egenskapen). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Hämtar eller anger Z‑ordningspositionen för textsignaturen. Bestämmer visningsordningen för överlappande signaturer. |

### Anmärkningar

**Learn more**

* Basic usage of creating Barcode electronic signature by GroupDocs.Signature: [How to eSign document with Barcode signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Barcode signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Se även

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
