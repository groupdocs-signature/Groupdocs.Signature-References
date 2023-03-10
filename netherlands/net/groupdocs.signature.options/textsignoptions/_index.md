---
title: TextSignOptions
second_title: GroupDocs.Signature voor .NET API-referentie
description: Vertegenwoordigt de teksthandtekeningopties.
type: docs
weight: 1730
url: /nl/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Vertegenwoordigt de teksthandtekeningopties.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | Initialiseert een nieuwe instantie van de klasse TextSignOptions met standaardwaarden. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | Initialiseert een nieuwe instantie van de klasse TextSignOptions met text. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Zet handtekening op alle documentpagina's. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Extra uiterlijk van handtekening. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Haalt of stelt de achtergrondinstellingen van de handtekening in. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Randinstellingen opgeven |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Haal het documenttype van de handtekeningopties op of stel het in[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Handtekeningextensies. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Hiermee wordt het lettertype van de handtekening opgehaald of ingesteld. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Hiermee wordt de voorgrondkleur van de handtekening opgehaald of ingesteld. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Haalt de titel van het tekstformulierveld op of stelt deze in om er een teksthandtekening in te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Hiermee wordt het type formulierveld opgehaald of ingesteld om er een teksthandtekening in te plaatsen. Deze eigenschap kan alleen worden gebruikt met SignatureImplementation = TextToFormField. De standaardwaarde is AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Handtekeninghoogte op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) Eigenschap SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontale uitlijning van handtekening op documentpagina. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Linker X-positie van handtekening op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) Eigenschap LocationMeasureType). (werkt als horizontale uitlijning niet is opgegeven). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor eigenschappen Links en Boven. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Hiermee wordt de ruimte tussen de randen van Sign en Document opgehaald of ingesteld. (werkt ALLEEN als horizontale of verticale uitlijning is opgegeven). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Haalt het meettype op of stelt het in (pixels, procenten of millimeters) voor Marge. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Haalt of stelt het native attribuut in. Als dit is ingesteld, kunnen documentspecifieke handtekeningen worden gebruikt. Eigen tekstwatermerk voor WordProcessing-documenten is bijvoorbeeld anders dan normaal. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Haalt of stelt documentpaginanummer in voor ondertekening. Minimale en standaardwaarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opties om pagina's op te geven die moeten worden ondertekend. |
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

* Basisgebruik van het maken van een elektronische teksthandtekening door GroupDocs.Signature: [Document e-ondertekenen met teksthandtekening](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Geavanceerd gebruik van instellingen van tekst elektronische handtekening met GroupDocs.Signature: [Geavanceerd gebruik van eSign-documenten met teksthandtekening en aanvullende instellingen](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Zie ook

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* naamruimte [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
