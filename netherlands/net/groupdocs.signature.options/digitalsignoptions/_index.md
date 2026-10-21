---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Stelt de digitale handtekeningopties voor."
type: docs
weight: 1560
url: /nl/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Stelt de digitale handtekeningopties voor.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met standaardwaarden. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatstroom. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatbestand. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatstroom en afbeeldingsstroom. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatstroom en afbeeldingsbestand. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatbestand en afbeeldingsstroom. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatbestand en afbeeldingsbestand. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Haalt of stelt een vlag in die ondertekenen met een certificaat waarvan de geldigheidsperiode is verlopen, toestaat. De standaardwaarde is false: ondertekenen met een verlopen certificaat veroorzaakt een [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), en het document wordt niet ondertekend. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Haalt of stelt een vlag in die ondertekenen met een certificaat waarvan de geldigheidsperiode nog niet is begonnen, toestaat. De standaardwaarde is false: ondertekenen met een dergelijk certificaat veroorzaakt een [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), en het document wordt niet ondertekend. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Plaats handtekening op alle documentpagina's. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aanvullende handtekeningweergave. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specificeer randinstellingen |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Haalt of stelt het bestandspad van het digitale certificaat in. Deze eigenschap wordt alleen gebruikt als CertificateStream niet is opgegeven. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Haalt of stelt de digitale certificaatstroom in. Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Haalt of stelt het handtekeningcontact in. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Haalt of stelt een aangepaste hash-ondertekeningsfunctie in, waarmee gebruikers hun eigen digitale ondertekeningslogica kunnen implementeren. Dit maakt ondertekenen met externe certificaten mogelijk en ondersteunt verschillende hash-algoritmen. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Haalt het documenttype van de handtekeningopties op of stelt het in [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Handtekeningextensies. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Haalt het hash-algoritme op dat moet worden gebruikt voor cryptografische bewerkingen, of stelt dit in. Alleen ondersteund voor digitale handtekeningen in PDF-bestanden. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Hoogte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters, zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontale uitlijning van de handtekening op de documentpagina. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Geeft of stelt het bestandspad van de handtekeningafbeelding in. Deze eigenschap wordt alleen gebruikt als ImageStream niet is gespecificeerd. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Geeft of stelt de handtekeningafbeeldingsstroom in. Als deze eigenschap is gespecificeerd, wordt deze altijd gebruikt in plaats van ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Linker X-positie van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (werkt als horizontale uitlijning niet is gespecificeerd). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Haalt op of stelt de handtekeninglocatie in. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Links en Boven. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Geeft of stelt de ruimte tussen handtekening en documentranden in. (werkt ALLEEN als horizontale of verticale uitlijning is gespecificeerd). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Geeft of stelt het meettype (pixels, procenten of millimeters) voor marge in. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Geeft of stelt het paginanummer van het document voor ondertekening in. Minimale en standaardwaarde is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opties om pagina's op te geven die ondertekend moeten worden. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Haalt op of stelt het wachtwoord van het digitale certificaat in. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Haalt op of stelt de reden van de handtekening in. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rechthoek van het gebied waarin de afbeelding op het document wordt geplaatst. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotatiehoek van de handtekening op de documentpagina (met de klok mee). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definieert waar de vorm moet worden gepresenteerd in de documentlay-out. Alleen beschikbaar voor Word-documenten. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Haalt op of stelt eigenschappen van de digitale handtekening van het document in. Voor het ondertekenen van Pdf-documenten is het mogelijk om geavanceerde eigenschappen in te stellen door een instantie van [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) te gebruiken. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Haal het handtekeningtype op [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Rekmodus op Documentpagina. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Bovenste Y-positie van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters zie [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (werkt als verticale uitlijning niet is gespecificeerd). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Geeft of stelt de transparantie van de handtekening in (waarde van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig)). Standaardwaarde is 0 (ondoorzichtig). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Haalt op/stelt de ltv (Long Term Validation) validatievlag in. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Verticale uitlijning van de handtekening op de documentpagina. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Haalt op of stelt de zichtbaarheid van de handtekening in. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Breedte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES type [`XAdESType`](./xadestype). Standaardwaarde is None (XAdES is uitgeschakeld). Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Geeft of stelt de Z-order positie van de teksthandtekening in. Bepaalt de weergavevolgorde van overlappende handtekeningen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Wis interne bronnen |

### Opmerkingen

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Zie ook

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
