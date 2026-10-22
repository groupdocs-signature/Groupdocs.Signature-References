---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Representerar QRCode‑signaturalternativen."
type: docs
weight: 1920
url: /sv/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Representerar QR‑kodsignaturalternativen.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Initierar en ny instans av klassen QRCodeSignOptions med standardvärden. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Initierar en ny instans av klassen QRCodeSignOptions med text. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Initierar en ny instans av klassen BarcodeSignOptions med text. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Placera signatur på alla dokumentsidor. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Hämtar eller anger bakgrundsinställningarna för signaturen. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Ange kantinställningar |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Hämtar eller anger justeringen av text i den resulterande QR‑kod‑bilden. Standardvärdet är None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Hämtar eller anger anpassat objekt för serialisering till QR‑Code‑innehåll. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Hämtar eller anger implementation av [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)-gränssnittet för att koda och avkoda QR-Code-signaturens Text- eller Data-egenskaper. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ange dokumenttypen för signaturalternativen [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Hämtar eller anger QR‑Code‑typ. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Hämtar eller anger teckensnittet för signaturen. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Hämtar eller anger förgrundsfärgen för QR‑Code‑staplar. Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Hämtar eller anger titeln på textformulärfältet för att placera textsignatur i det. Denna egenskap kan endast användas med SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Hämtar eller anger typen av formulärfält för att placera textsignatur i det. Denna egenskap kan endast användas med SignatureImplementation = TextToFormField. Standardvärdet är AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer. Stöds uteslutande för digitala signaturer i PDF‑filer. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Höjd på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType‑egenskapen). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horisontell justering av signaturen på dokumentsidan. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Hämtar eller anger avståndet mellan QR‑Code‑element och bildens kant. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Vänster X‑position för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType‑egenskapen). (fungerar om horisontell justering inte är specificerad). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för Left- och Top‑egenskaper. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Hämtar eller anger filnamnet för QR‑code‑logobilden. Denna egenskap används endast om LogoStream inte är specificerad. Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Hämtar eller anger strömmen för QR‑code‑logobilden. Om denna egenskap är specificerad används den alltid istället för LogoFilePath. Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Hämtar eller anger avståndet mellan signatur och dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är angiven). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Hämtar eller anger måtttypen (pixlar, procent eller millimeter) för marginal. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Hämtar eller anger den inhemska attributen. Om den är angiven kan dokumentspecifika signaturer användas. Inbyggt textvattenmärke för WordProcessing‑dokument är till exempel annorlunda än vanliga. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller anger dokumentsidans nummer för signering. Minimalt och standardvärde är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange vilka sidor som ska signeras. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Hämtar eller anger flagga för att hämta QR‑Code‑bildinnehåll för en signatur som placerats på dokumentsidan. Om flaggan är satt till true behåller QR‑Code‑signaturens bildinnehåll rå bilddata i det krävs formatet [`ReturnContentType`](./returncontenttype). Som standard är detta alternativ inaktiverat. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Anger filtyp för återgivet bildinnehåll för QR‑Code‑signaturen när egenskapen ReturnContent är aktiverad. Som standard är den satt till Null. Det innebär att QR‑Code‑bildinnehållet returneras i originalformat. Detta bildformat anges i [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Möjliga stödjade värden är: FileType.JPEG, FileType.PNG, FileType.BMP. Om angivet format inte stöds returneras QR‑Code‑bildinnehållet i .png‑format. |
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

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Se även

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
