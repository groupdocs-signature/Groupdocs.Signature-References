---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Stelt de Barcode-handtekeningopties voor."
type: docs
weight: 1450
url: /nl/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Stelt de Barcode-handtekeningopties voor.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Initialiseert een nieuw exemplaar van de BarcodeSignOptions-klasse met standaardwaarden. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions-klasse met tekst. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions-klasse met tekst. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Plaats handtekening op alle documentpagina's. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aanvullende handtekeningweergave. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Haalt op of stelt de achtergrondinstellingen van de handtekening in. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specificeer randinstellingen |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Haalt op of stelt de uitlijning van tekst in de resulterende Barcode-afbeelding in. Standaardwaarde is None. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Haalt het documenttype van de handtekeningopties op of stelt het in [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Haalt op of stelt het Barcode-type in. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Handtekeningextensies. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Haalt op of stelt het lettertype van de handtekening in. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Haalt op of stelt de Fore-kleur van Barcode-strepen in. Het gebruik van deze eigenschap kan problemen veroorzaken bij verificatie. Gebruik deze voorzichtig. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Haalt op of stelt de titel van het tekstformulierveld in om de teksthandtekening erin te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Haalt op of stelt het type formulierveld in om de teksthandtekening erin te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. Standaardwaarde is AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Haalt het hash-algoritme op dat moet worden gebruikt voor cryptografische bewerkingen, of stelt dit in. Alleen ondersteund voor digitale handtekeningen in PDF-bestanden. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Hoogte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType-eigenschap). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontale uitlijning van de handtekening op de documentpagina. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Haalt op of stelt de ruimte tussen Barcode-elementen en de randen van de resulterende afbeelding in. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Linker X‑positie van handtekening op documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) eigenschap LocationMeasureType). (werkt als horizontale uitlijning niet is gespecificeerd). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Links en Boven. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Geeft of stelt de ruimte tussen handtekening en documentranden in. (werkt ALLEEN als horizontale of verticale uitlijning is gespecificeerd). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Geeft of stelt het meettype (pixels, procenten of millimeters) voor marge in. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Krijgt of stelt het native‑attribuut in. Als het is ingesteld, kunnen documentspecifieke handtekeningen worden gebruikt. Native tekstwatermerk voor WordProcessing‑documenten is bijvoorbeeld anders dan reguliere. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Geeft of stelt het paginanummer van het document voor ondertekening in. Minimale en standaardwaarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opties om pagina's op te geven die ondertekend moeten worden. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Krijgt of stelt de vlag in om de barcode‑afbeeldingsinhoud van een handtekening die op de documentpagina is geplaatst op te halen. Als deze vlag op true wordt gezet, behoudt de barcode‑handtekeningafbeeldingsinhoud de ruwe afbeeldingsgegevens in het vereiste formaat [`ReturnContentType`](./returncontenttype). Standaard is deze optie uitgeschakeld. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | Specificeert het bestandstype van de geretourneerde afbeeldingsinhoud van de barcode‑handtekening wanneer de eigenschap ReturnContent is ingeschakeld. Standaard is deze ingesteld op Null. Dat betekent dat de barcode‑afbeeldingsinhoud in het oorspronkelijke formaat wordt geretourneerd. Dit afbeeldingsformaat wordt gespecificeerd bij [`Format`](../../groupdocs.signature.domain/barcodesignature/format). Mogelijke ondersteunde waarden zijn: FileType.JPEG, FileType.PNG, FileType.BMP. Als het opgegeven formaat niet wordt ondersteund, wordt de barcode‑afbeeldingsinhoud in .png‑formaat geretourneerd. |
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

* Basic usage of creating Barcode electronic signature by GroupDocs.Signature: [How to eSign document with Barcode signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Barcode signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Zie ook

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
