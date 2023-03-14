---
title: StampSignOptions
second_title: GroupDocs.Signature voor .NET API-referentie
description: Vertegenwoordigt de stempelhandtekeningopties.
type: docs
weight: 1710
url: /nl/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Vertegenwoordigt de stempelhandtekeningopties.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Initialiseert een nieuwe instantie van de klasse StampSignOptions met standaardwaarden. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Initialiseert een nieuwe instantie van de klasse StampSignOptions met uitlijningsopties. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Handtekening op alle documentpagina's plaatsen. Deze eigenschap kan alleen worden gebruikt voor beeldformaten met meerdere frames (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Extra uiterlijk van handtekening. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Haalt de stempelachtergrond op of stelt deze in. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Haalt of stelt het achtergrondkleuruitsnedetype van de handtekening in. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Hiermee wordt het bijsnijdtype van de achtergrondafbeelding van de handtekening opgehaald of ingesteld. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Randinstellingen opgeven |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Haal het documenttype van de handtekeningopties op of stel het in[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Handtekeningextensies. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Handtekeninghoogte op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontale uitlijning van handtekening op documentpagina. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Hiermee wordt het pad naar het handtekeningafbeeldingsbestand opgehaald of ingesteld. Deze eigenschap wordt alleen gebruikt als ImageStream niet is opgegeven. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Hiermee wordt de handtekeningafbeeldingsstroom opgehaald of ingesteld. Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats daarvan ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Lijst met binnenlijnen weergegeven als set rechthoeken. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Linker X-positie van handtekening op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (werkt als horizontale uitlijning niet is opgegeven). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor eigenschappen Links en Boven. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Hiermee wordt de ruimte tussen de randen van Sign en Document opgehaald of ingesteld. (werkt ALLEEN als horizontale of verticale uitlijning is opgegeven). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Haalt het meettype op of stelt het in (pixels, procenten of millimeters) voor Marge. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Lijst met buitenste lijnen weergegeven als concentrische cirkels. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Haalt of stelt documentpaginanummer in voor ondertekening. Minimale en standaardwaarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opties om pagina's op te geven die moeten worden ondertekend. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rechthoek van gebied om de afbeelding op document te plaatsen. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotatiehoek van handtekening op documentpagina (met de klok mee). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Verkrijg het handtekeningtype[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Breedte en Hoogte. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Hiermee wordt het stempeltype opgehaald of ingesteld. De standaardwaarde is Round. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Rekmodus op documentpagina. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Positie van handtekening op documentpagina in Meetwaarden (pixels, procenten of millimeters zie[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (werkt als verticale uitlijning niet is opgegeven). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Hiermee wordt de transparantie van de handtekening opgehaald of ingesteld (waarde van 0,0 (ondoorzichtig) tot 1,0 (helder)). Standaardwaarde is 0 (ondoorzichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Verticale uitlijning van handtekening op documentpagina. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Breedte van handtekening op documentpagina in Meetwaarden (pixels, procenten of millimeters[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Haalt de Z-volgordepositie van de teksthandtekening op of stelt deze in. Bepaalt de weergavevolgorde van overlappende handtekeningen. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Wist interne bronnen |

### Opmerkingen

**Kom meer te weten**

* Basisgebruik van het maken van een elektronische stempelstempel door GroupDocs.Signature: [Document e-ondertekenen met stempelhandtekening](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Geavanceerd gebruik van instellingen van Stempel elektronische handtekening met GroupDocs.Signature: [Geavanceerd gebruik van eSign-documenten met stempelhandtekening en aanvullende instellingen](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Zie ook

* class [ImageSignOptions](../imagesignoptions)
* naamruimte [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
