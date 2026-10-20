---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Stellt die digitalen Signaturoptionen dar."
type: docs
weight: 1560
url: /de/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Stellt die digitalen Signaturoptionen dar.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Standardwerten. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit einem Zertifikat-Stream. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit einer Zertifikatsdatei. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit einem Zertifikat-Stream und einem Bild-Stream. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit einem Zertifikat-Stream und einer Bilddatei. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit einer Zertifikatsdatei und einem Bild-Stream. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit einer Zertifikatsdatei und einer Bilddatei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Liest oder setzt ein Flag, das das Signieren mit einem Zertifikat ermöglicht, dessen Gültigkeitszeitraum abgelaufen ist. Der Standardwert ist false: Das Signieren mit einem abgelaufenen Zertifikat löst [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) aus, und das Dokument wird nicht signiert. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Liest oder setzt ein Flag, das das Signieren mit einem Zertifikat ermöglicht, dessen Gültigkeitszeitraum noch nicht begonnen hat. Der Standardwert ist false: Das Signieren mit einem solchen Zertifikat löst [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) aus, und das Dokument wird nicht signiert. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Signatur auf allen Dokumentseiten platzieren. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Zusätzliches Signatur‑Erscheinungsbild. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Rahmeneinstellungen angeben |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Liest oder setzt den Pfad zur digitalen Zertifikatsdatei. Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Liest oder setzt den digitalen Zertifikat-Stream. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateFilePath verwendet. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Liest oder setzt den Signaturkontakt. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Liest oder setzt eine benutzerdefinierte Hash-Signaturfunktion, die es Benutzern ermöglicht, ihre eigene digitale Signaturlogik zu implementieren. Dies ermöglicht das Signieren mit externen Zertifikaten und unterstützt verschiedene Hash-Algorithmen. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signatur‑Erweiterungen. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Liest oder legt den Hash‑Algorithmus fest, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontale Ausrichtung der Signatur auf der Dokumentseite. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Liest oder legt den Dateipfad des Signatur‑Bildes fest. Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Liest oder legt den Signatur‑Bild‑Stream fest. Wenn diese Eigenschaft angegeben ist, wird sie stets anstelle von ImageFilePath verwendet. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Linke X‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funktioniert, wenn die horizontale Ausrichtung nicht angegeben ist). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Liest oder setzt den Signaturort. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Left und Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Liest oder legt den Abstand zwischen Signatur und Dokumentkanten fest. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Liest oder legt den Messwerttyp (Pixel, Prozentsätze oder Millimeter) für den Rand fest. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Liest oder legt die Dokumentseitennummer für die Signatur fest. Minimaler und Standardwert ist 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Optionen zum Angeben der zu signierenden Seiten. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Liest oder setzt das Passwort des digitalen Zertifikats. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Liest oder setzt den Grund der Signatur. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rechteck des Bereichs, in dem das Bild im Dokument platziert wird. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word‑Dokumente verfügbar. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Liest oder setzt Eigenschaften der digitalen Dokumentensignatur. Für das Signieren von PDF-Dokumenten ist es möglich, erweiterte Eigenschaften zu setzen, indem man eine Instanz von [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) verwendet. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Abrufen des Signaturtyps [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Dehnungsmodus auf der Dokumentseite. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (Funktioniert, wenn die vertikale Ausrichtung nicht angegeben ist). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Liest oder setzt die Transparenz der Signatur (Wert von 0,0 (undurchsichtig) bis 1,0 (transparent)). Standardwert ist 0 (undurchsichtig). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Liest/setzt das ltv (Long Term Validation)-Validierungsflag. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikale Ausrichtung der Signatur auf der Dokumentseite. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Liest oder setzt die Sichtbarkeit der Signatur. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES-Typ [`XAdESType`](./xadestype). Standardwert ist None (XAdES ist deaktiviert). In diesem Moment wird der XAdES-Signaturtyp nur für Tabellenkalkulationsdokumente unterstützt. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Liest oder setzt die Z‑Reihenfolge‑Position der Textsignatur. Bestimmt die Anzeigereihenfolge überlappender Signaturen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Löscht interne Ressourcen |

### Hinweise

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Siehe auch

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
