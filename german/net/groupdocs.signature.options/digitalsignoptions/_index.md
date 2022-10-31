---
title: DigitalSignOptions
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Repräsentiert die Optionen für digitale Signaturen.
type: docs
weight: 1260
url: /de/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Repräsentiert die Optionen für digitale Signaturen.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Standardwerten. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Zertifikatstrom. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Zertifikatsdatei. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Zertifikat-Stream und Bild-Stream. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Zertifikat-Stream und Bilddatei. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Zertifikatsdatei und Bildstream. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initialisiert eine neue Instanz der DigitalSignOptions-Klasse mit Zertifikatsdatei und Bilddatei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Signatur auf allen Dokumentseiten platzieren. Diese Eigenschaft kann nur für Bildformate mit mehreren Frames (Tiff) verwendet werden. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Zusätzliche Signaturdarstellung. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Rahmeneinstellungen festlegen |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Ruft den Dateipfad des digitalen Zertifikats ab oder legt ihn fest. Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Holt oder setzt digitalen Zertifikatstrom. Wenn diese Eigenschaft angegeben ist, wird sie immer stattdessen verwendet CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Ruft den Signaturkontakt ab oder legt ihn fest. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturerweiterungen. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Höhe der Unterschrift auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter s[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontale Ausrichtung der Signatur auf der Dokumentenseite. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Ruft den Pfad der Signaturbilddatei ab oder legt ihn fest. Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Holt oder setzt den Signaturbildstream. Wenn diese Eigenschaft angegeben ist, wird sie immer stattdessen verwendet ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Linke X-Position der Signatur auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter siehe[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funktioniert, wenn keine horizontale Ausrichtung angegeben ist). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Ruft den Signaturspeicherort ab oder legt ihn fest. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Maßtyp (Pixel, Prozent oder Millimeter) für Left- und Top-Eigenschaften. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Ruft den Abstand zwischen Zeichen- und Dokumentkanten ab oder legt ihn fest. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Ruft den Maßtyp (Pixel, Prozent oder Millimeter) für den Rand ab oder legt ihn fest. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ruft die Seitenzahl des Dokuments zum Signieren ab oder legt sie fest. Minimal- und Standardwert ist 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Optionen zum Angeben von Seiten, die signiert werden sollen. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Ruft das Passwort des digitalen Zertifikats ab oder legt es fest. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Ruft den Signaturgrund ab oder legt ihn fest. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rechteck des Bereichs, um das Bild auf dem Dokument zu platzieren. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationswinkel der Unterschrift auf der Dokumentenseite (im Uhrzeigersinn). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Ruft die Eigenschaften der digitalen Signatur des Dokuments ab oder legt sie fest. Zum Signieren von PDF-Dokumenten ist es möglich, erweiterte Eigenschaften festzulegen, indem Sie die Instanz von verwenden[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Holen Sie sich den Signaturtyp[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Maßtyp (Pixel, Prozent oder Millimeter) für Breiten- und Höheneigenschaften. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Dehnungsmodus auf Dokumentseite. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Position der Unterschrift auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter s[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funktioniert, wenn keine vertikale Ausrichtung angegeben ist). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Holt oder setzt die Signaturtransparenz (Wert von 0,0 (undurchsichtig) bis 1,0 (klar)). Der Standardwert ist 0 (undurchsichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikale Ausrichtung der Signatur auf der Dokumentenseite. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Ruft die Sichtbarkeit der Signatur ab oder legt sie fest. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Breite der Signatur auf der Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES-Typ[`XAdESType`](./xadestype) . Der Standardwert ist „None“ (XAdES ist deaktiviert). Derzeit wird der XAdES-Signaturtyp nur für Spreadsheet-Dokumente unterstützt. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ruft die Position der Textsignatur in Z-Reihenfolge ab oder legt sie fest. Legt die Anzeigereihenfolge überlappender Signaturen fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Löscht interne Ressourcen |

### Bemerkungen

**Mehr erfahren**

* Grundlegende Verwendung zum Erstellen einer digitalen elektronischen Signatur durch GroupDocs.Signature: [So signieren Sie ein Dokument mit einer digitalen Signatur](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Erweiterte Nutzung der Einstellungen der digitalen elektronischen Signatur mit GroupDocs.Signature: [Erweiterte Nutzung zum eSignieren von Dokumenten mit digitaler Signatur und zusätzlichen Einstellungen](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Siehe auch

* class [ImageSignOptions](../imagesignoptions)
* namensraum [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
