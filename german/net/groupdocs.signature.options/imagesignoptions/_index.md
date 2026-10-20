---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Stellt die Bildsignaturoptionen dar."
type: docs
weight: 1670
url: /de/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Stellt die Bildsignaturoptionen dar.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Initialisiert eine neue Instanz der Klasse ImageSignOptions mit Standardwerten. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Initialisiert eine neue Instanz der Klasse ImageSignOptions mit einem Bild‑Stream. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Initialisiert eine neue Instanz der Klasse ImageSignOptions mit einer Bilddatei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Signatur auf allen Dokumentseiten platzieren. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Zusätzliches Signatur‑Erscheinungsbild. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Rahmeneinstellungen angeben |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signatur‑Erweiterungen. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Liest oder legt den Hash‑Algorithmus fest, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontale Ausrichtung der Signatur auf der Dokumentseite. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Liest oder legt den Dateipfad des Signatur‑Bildes fest. Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Liest oder legt den Signatur‑Bild‑Stream fest. Wenn diese Eigenschaft angegeben ist, wird sie stets anstelle von ImageFilePath verwendet. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Linke X‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funktioniert, wenn die horizontale Ausrichtung nicht angegeben ist). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Left und Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Liest oder legt den Abstand zwischen Signatur und Dokumentkanten fest. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Liest oder legt den Messwerttyp (Pixel, Prozentsätze oder Millimeter) für den Rand fest. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Liest oder legt die Dokumentseitennummer für die Signatur fest. Minimaler und Standardwert ist 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Optionen zum Angeben der zu signierenden Seiten. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rechteck des Bereichs, in dem das Bild im Dokument platziert wird. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word‑Dokumente verfügbar. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Abrufen des Signaturtyps [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Dehnungsmodus auf der Dokumentseite. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (Funktioniert, wenn die vertikale Ausrichtung nicht angegeben ist). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Liest oder setzt die Transparenz der Signatur (Wert von 0,0 (undurchsichtig) bis 1,0 (transparent)). Standardwert ist 0 (undurchsichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikale Ausrichtung der Signatur auf der Dokumentseite. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Liest oder setzt die Z‑Reihenfolge‑Position der Textsignatur. Bestimmt die Anzeigereihenfolge überlappender Signaturen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Erstellt eine neue Instanz der Klasse ImageSignOptions mit einem vordefinierten Bild aus Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Löscht interne Ressourcen |

### Hinweise

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Siehe auch

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
