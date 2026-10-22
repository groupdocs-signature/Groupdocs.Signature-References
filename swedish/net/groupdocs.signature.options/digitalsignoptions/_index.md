---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Representerar alternativen för digital signatur."
type: docs
weight: 1560
url: /sv/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Representerar alternativen för digital signatur.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initierar en ny instans av klassen DigitalSignOptions med standardvärden. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildström. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildfil. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildström. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildfil. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut. Standardvärdet är false: signering med ett utgånget certifikat kastar [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), och dokumentet signeras inte. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat. Standardvärdet är false: signering med ett sådant certifikat kastar [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), och dokumentet signeras inte. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Placera signatur på alla dokumentsidor. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ytterligare signaturutseende. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Ange kantinställningar |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Hämtar eller anger sökvägen till den digitala certifikatfilen. Denna egenskap används endast om CertificateStream inte är angiven. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Hämtar eller anger digital certifikatström. Om denna egenskap är angiven används den alltid i stället för CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Hämtar eller anger signaturens kontakt. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Hämtar eller anger en anpassad hash‑signeringsfunktion, vilket låter användare implementera sin egen digitala signeringslogik. Detta möjliggör signering med externa certifikat och stödjer olika hash‑algoritmer. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Hämta eller ange dokumenttypen för signaturalternativen [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturtillägg. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer. Stöds uteslutande för digitala signaturer i PDF‑filer. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Höjd på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horisontell justering av signaturen på dokumentsidan. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Hämtar eller anger sökvägen till signaturens bildfil. Denna egenskap används endast om ImageStream inte är angiven. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Hämtar eller anger signaturens bildström. Om denna egenskap är angiven används den alltid istället för ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Vänster X‑position för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om horisontell justering inte är angiven). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Hämtar eller anger signaturens plats. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för Left- och Top‑egenskaper. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Hämtar eller anger avståndet mellan signatur och dokumentkanter. (fungerar ENDAST om horisontell eller vertikal justering är angiven). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Hämtar eller anger måtttypen (pixlar, procent eller millimeter) för marginal. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Hämtar eller anger dokumentsidans nummer för signering. Minimalt och standardvärde är 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Alternativ för att ange vilka sidor som ska signeras. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Hämtar eller anger lösenordet för det digitala certifikatet. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Hämtar eller anger anledningen till signaturen. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rektangel för området där bilden ska placeras i dokumentet. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationsvinkel för signaturen på dokumentsidan (medurs). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definierar var formen ska visas i dokumentlayouten. Tillgänglig endast för Word‑dokument. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Hämtar eller anger egenskaper för dokumentets digitala signatur. För signering av PDF‑dokument är det möjligt att ange avancerade egenskaper genom att använda en instans av [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Hämta signaturtypen [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Måtttyp (pixlar, procent eller millimeter) för Width- och Height‑egenskaper. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Stretch‑läge på dokumentsidan. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Övre Y‑position för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter, se [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (fungerar om vertikal justering inte är angiven). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Hämtar eller anger signaturens transparens (värde från 0,0 (opak) till 1,0 (genomskinlig)). Standardvärdet är 0 (opak). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Hämtar/anger ltv (Long Term Validation) valideringsflagga. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikal justering av signaturen på dokumentsidan. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Hämtar eller anger signaturens synlighet. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Bredd på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES-typ [`XAdESType`](./xadestype). Standardvärdet är None (XAdES är avstängt). För närvarande stöds XAdES-signaturtyp endast för Spreadsheet-dokument. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Hämtar eller anger Z‑ordningspositionen för textsignaturen. Bestämmer visningsordningen för överlappande signaturer. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Rensar interna resurser |

### Anmärkningar

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Se även

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
