---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Geeft de QRCode-handtekeningopties weer."
type: docs
weight: 1920
url: /nl/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Geeft de QR-code-handtekeningopties weer.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Initialiseert een nieuw exemplaar van de QRCodeSignOptions-klasse met standaardwaarden. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Initialiseert een nieuw exemplaar van de QRCodeSignOptions-klasse met tekst. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions-klasse met tekst. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Plaats handtekening op alle documentpagina's. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aanvullende handtekeningweergave. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Haalt op of stelt de achtergrondinstellingen van de handtekening in. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specificeer randinstellingen |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Haalt op of stelt de uitlijning van tekst in de resulterende QR-code-afbeelding in. Standaardwaarde is None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Haalt op of stelt een aangepast object in om te serialiseren naar QR-Code-inhoud. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Haalt of stelt de implementatie van de [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Haalt het documenttype van de handtekeningopties op of stelt het in [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Haalt op of stelt QR-Code type in. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Handtekeningextensies. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Haalt op of stelt het lettertype van de handtekening in. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Haalt op of stelt de voorkleur van QR-Code balken in. Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik deze zorgvuldig. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Haalt op of stelt de titel van het tekstformulierveld in om de teksthandtekening erin te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Haalt op of stelt het type formulierveld in om de teksthandtekening erin te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. Standaardwaarde is AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Haalt het hash-algoritme op dat moet worden gebruikt voor cryptografische bewerkingen, of stelt dit in. Alleen ondersteund voor digitale handtekeningen in PDF-bestanden. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Hoogte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType-eigenschap). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontale uitlijning van de handtekening op de documentpagina. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Haalt op of stelt de ruimte tussen QR-Code elementen en de randen van de resulterende afbeelding in. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Linker X‑positie van handtekening op documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) eigenschap LocationMeasureType). (werkt als horizontale uitlijning niet is gespecificeerd). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Links en Boven. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Haalt op of stelt de bestandsnaam van de QR-code logo-afbeelding in. Deze eigenschap wordt alleen gebruikt als LogoStream niet is opgegeven. Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik deze zorgvuldig. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Haalt op of stelt de QR-code logo-afbeeldingsstroom in. Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van LogoFilePath. Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik deze zorgvuldig. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Geeft of stelt de ruimte tussen handtekening en documentranden in. (werkt ALLEEN als horizontale of verticale uitlijning is gespecificeerd). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Geeft of stelt het meettype (pixels, procenten of millimeters) voor marge in. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Krijgt of stelt het native‑attribuut in. Als het is ingesteld, kunnen documentspecifieke handtekeningen worden gebruikt. Native tekstwatermerk voor WordProcessing‑documenten is bijvoorbeeld anders dan reguliere. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Geeft of stelt het paginanummer van het document voor ondertekening in. Minimale en standaardwaarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opties om pagina's op te geven die ondertekend moeten worden. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Haalt op of stelt de vlag in om de QR-Code afbeeldingsinhoud van een handtekening die op een documentpagina is geplaatst op te halen. Als deze vlag true is, behoudt de QR-Code handtekening afbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat [`ReturnContentType`](./returncontenttype). Standaard is deze optie uitgeschakeld. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code handtekening wanneer de ReturnContent‑eigenschap is ingeschakeld. Standaard is deze ingesteld op Null. Dat betekent dat de QR-Code afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd. Dit afbeeldingsformaat wordt gespecificeerd bij [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP. Als het opgegeven formaat niet wordt ondersteund, wordt de QR-Code afbeeldingsinhoud in .png‑formaat geretourneerd. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotatiehoek van de handtekening op de documentpagina (met de klok mee). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Definieert waar de vorm moet worden gepresenteerd in de documentlay-out. Alleen beschikbaar voor Word-documenten. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Krijgt of stelt het type vorm in om tekst te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextStamp. Standaardwaarde is Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Krijgt of stelt de unieke ID van de handtekening in. Deze kan worden gebruikt in verificatie‑opties voor handtekeningen. Eigenschap wordt alleen ondersteund voor Pdf‑documenten. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Krijgt of stelt het type implementatie van tekst‑handtekening in. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Haal het handtekeningtype op [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Rekmodus op Documentpagina. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Krijgt of stelt de tekst van de handtekening in. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Horizontale uitlijning van tekst binnen een handtekening. Deze functie wordt alleen ondersteund voor Image‑ en Annotation‑handtekeningimplementaties (zie [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) eigenschap SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Verticale uitlijning van tekst binnen een handtekening. Deze functie wordt alleen ondersteund voor Image‑handtekeningimplementatie (zie [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) eigenschap SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Bovenste Y‑positie van handtekening op documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) eigenschap LocationMeasureType). (werkt als verticale uitlijning niet is gespecificeerd). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Geeft of stelt de transparantie van de handtekening in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). Standaardwaarde is 0 (ondoorzichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Verticale uitlijning van de handtekening op de documentpagina. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Breedte van handtekening op documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) eigenschap SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Geeft of stelt de Z-order positie van de teksthandtekening in. Bepaalt de weergavevolgorde van overlappende handtekeningen. |

### Opmerkingen

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Zie ook

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
