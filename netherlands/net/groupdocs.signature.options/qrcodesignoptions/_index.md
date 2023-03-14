---
title: QrCodeSignOptions
second_title: GroupDocs.Signature voor .NET API-referentie
description: Vertegenwoordigt de handtekeningopties van de QRcode.
type: docs
weight: 1630
url: /nl/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Vertegenwoordigt de handtekeningopties van de QR-code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Initialiseert een nieuwe instantie van de klasse QRCodeSignOptions met standaardwaarden. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Initialiseert een nieuwe instantie van de klasse QRCodeSignOptions met tekst. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Initialiseert een nieuwe instantie van de klasse BarcodeSignOptions met tekst. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Zet handtekening op alle documentpagina's. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Extra uiterlijk van handtekening. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Haalt of stelt de achtergrondinstellingen van de handtekening in. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Randinstellingen opgeven |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Hiermee wordt de uitlijning van tekst in de resulterende QR-codeafbeelding opgehaald of ingesteld. Standaardwaarde is Geen. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Krijgt of stelt een aangepast object in om te serialiseren naar QR-code-inhoud. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Haalt of stelt implementatie in van[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface voor het coderen en decoderen van QR-code Handtekening Tekst of gegevenseigenschappen. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Haal het documenttype van de handtekeningopties op of stel het in[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Krijgt of stelt het type QR-code in. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Handtekeningextensies. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Hiermee wordt het lettertype van de handtekening opgehaald of ingesteld. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Krijgt of stelt de voorkleur van QR-codebalken in Het gebruik van deze eigenschap kan problemen met de verificatie veroorzaken. Gebruik het voorzichtig. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Haalt de titel van het tekstformulierveld op of stelt deze in om er een teksthandtekening in te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Hiermee wordt het type formulierveld opgehaald of ingesteld om er een teksthandtekening in te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. De standaardwaarde is AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Handtekeninghoogte op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) Eigenschap SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontale uitlijning van handtekening op documentpagina. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Haalt of stelt de ruimte in tussen QR-code-elementen en resultaatafbeeldingsranden. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Linker X-positie van handtekening op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) Eigenschap LocationMeasureType). (werkt als horizontale uitlijning niet is opgegeven). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor eigenschappen Links en Boven. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Hiermee wordt de bestandsnaam van het logo van het logo van de QR-code opgehaald of ingesteld. Deze eigenschap wordt alleen gebruikt als LogoStream niet is opgegeven. Het gebruik van deze eigenschap kan problemen met de verificatie veroorzaken. Gebruik het voorzichtig. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Haalt of stelt de QR-code logo-beeldstream in. Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van LogoFilePath. Het gebruik van deze eigenschap kan problemen met de verificatie veroorzaken. Gebruik het voorzichtig. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Hiermee wordt de ruimte tussen de randen van Sign en Document opgehaald of ingesteld. (werkt ALLEEN als horizontale of verticale uitlijning is opgegeven). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Haalt het meettype op of stelt het in (pixels, procenten of millimeters) voor Marge. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Haalt of stelt het native attribuut in. Als dit is ingesteld, kunnen documentspecifieke handtekeningen worden gebruikt. Eigen tekstwatermerk voor WordProcessing-documenten is bijvoorbeeld anders dan normaal. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Haalt of stelt documentpaginanummer in voor ondertekening. Minimale en standaardwaarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opties om pagina's op te geven die moeten worden ondertekend. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Haalt een vlag op of stelt deze in om QR-code-afbeeldingsinhoud op te halen van een handtekening die op de documentpagina is geplaatst. Als deze vlag is ingesteld op True, behoudt de QR-code-handtekeningafbeeldingsinhoud onbewerkte afbeeldingsgegevens in het vereiste formaat[`ReturnContentType`](./returncontenttype) . Standaard is deze optie uitgeschakeld. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Specificeert het bestandstype van geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de eigenschap ReturnContent is ingeschakeld. Standaard ingesteld op Null. Dat betekent om QR-Code-afbeeldingsinhoud in origineel formaat terug te sturen. Dit afbeeldingsformaat is gespecificeerd op[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) Mogelijk ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP. Als het opgegeven formaat niet wordt ondersteund, wordt QR-code afbeeldingsinhoud in .png-formaat geretourneerd. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotatiehoek van handtekening op documentpagina (met de klok mee). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Hiermee wordt het type vorm opgehaald of ingesteld om tekst te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextStamp. De standaardwaarde is Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Haalt de unieke ID van de handtekening op of stelt deze in. Het kan worden gebruikt in opties voor handtekeningverificatie. Eigenschap wordt alleen ondersteund voor pdf-documenten. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Hiermee wordt het type implementatie van teksthandtekeningen opgehaald of ingesteld. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Verkrijg het handtekeningtype[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Breedte en Hoogte. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Rekmodus op documentpagina. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Haalt de tekst van de handtekening op of stelt deze in. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Horizontale uitlijning van tekst binnen een handtekening. Deze functie wordt alleen ondersteund voor implementaties van handtekeningen met afbeeldingen en annotaties (zie[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation-eigenschap). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Verticale uitlijning van tekst binnen een handtekening. Deze functie wordt alleen ondersteund voor implementatie van afbeeldingshandtekeningen (zie[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation-eigenschap). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Top Y Positie van handtekening op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype)Eigenschap LocationMeasureType). (werkt als verticale uitlijning niet is opgegeven). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Hiermee wordt de transparantie van de handtekening opgehaald of ingesteld (waarde van 0,0 (ondoorzichtig) tot 1,0 (helder)). Standaardwaarde is 0 (ondoorzichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Verticale uitlijning van handtekening op documentpagina. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Handtekeningbreedte op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) Eigenschap SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Haalt de Z-volgordepositie van de teksthandtekening op of stelt deze in. Bepaalt de weergavevolgorde van overlappende handtekeningen. |

### Opmerkingen

**Kom meer te weten**

* Basisgebruik van het maken van een QR-code elektronische handtekening door GroupDocs.Signature: [Document e-ondertekenen met QR-code handtekening](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Geavanceerd gebruik van instellingen van QR-Code elektronische handtekening met GroupDocs.Signature: [Geavanceerd gebruik van eSign-documenten met QR-Code-handtekening en aanvullende instellingen](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Zie ook

* class [TextSignOptions](../textsignoptions)
* naamruimte [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
