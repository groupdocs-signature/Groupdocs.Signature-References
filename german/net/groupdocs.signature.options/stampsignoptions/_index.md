---
title: StampSignOptions
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Repräsentiert die Stempelsignaturoptionen.
type: docs
weight: 1630
url: /de/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Repräsentiert die Stempelsignaturoptionen.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Initialisiert eine neue Instanz der StampSignOptions-Klasse mit Standardwerten. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Initialisiert eine neue Instanz der StampSignOptions-Klasse mit Ausrichtungsoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Signatur auf allen Dokumentseiten platzieren. Diese Eigenschaft kann nur für Bildformate mit mehreren Frames (Tiff) verwendet werden. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Zusätzliche Signaturdarstellung. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Ruft den Stempelhintergrund ab oder legt ihn fest. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Ruft den Beschneidungstyp der Hintergrundfarbe der Signatur ab oder legt ihn fest. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Ruft den Beschneidungstyp des Hintergrundbilds der Signatur ab oder legt ihn fest. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Rahmeneinstellungen festlegen |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturerweiterungen. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Höhe der Unterschrift auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter s[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontale Ausrichtung der Signatur auf der Dokumentenseite. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Ruft den Pfad der Signaturbilddatei ab oder legt ihn fest. Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Holt oder setzt den Signaturbildstream. Wenn diese Eigenschaft angegeben ist, wird sie immer stattdessen verwendet ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Liste der inneren Linien, die als Satz von Rechtecken gerendert werden. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Linke X-Position der Signatur auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter siehe[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funktioniert, wenn keine horizontale Ausrichtung angegeben ist). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Maßtyp (Pixel, Prozent oder Millimeter) für Left- und Top-Eigenschaften. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Ruft den Abstand zwischen Zeichen- und Dokumentkanten ab oder legt ihn fest. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Ruft den Maßtyp (Pixel, Prozent oder Millimeter) für den Rand ab oder legt ihn fest. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Liste der äußeren Linien, dargestellt als konzentrische Kreise. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ruft die Seitenzahl des Dokuments zum Signieren ab oder legt sie fest. Minimal- und Standardwert ist 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Optionen zum Angeben von Seiten, die signiert werden sollen. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rechteck des Bereichs, um das Bild auf dem Dokument zu platzieren. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotationswinkel der Unterschrift auf der Dokumentenseite (im Uhrzeigersinn). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Holen Sie sich den Signaturtyp[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Maßtyp (Pixel, Prozent oder Millimeter) für Breiten- und Höheneigenschaften. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Ruft den Stempeltyp ab oder legt ihn fest. Der Standardwert ist Rund. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Dehnungsmodus auf Dokumentseite. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Position der Unterschrift auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter s[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funktioniert, wenn keine vertikale Ausrichtung angegeben ist). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Holt oder setzt die Signaturtransparenz (Wert von 0,0 (undurchsichtig) bis 1,0 (klar)). Der Standardwert ist 0 (undurchsichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertikale Ausrichtung der Signatur auf der Dokumentenseite. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Breite der Signatur auf der Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ruft die Position der Textsignatur in Z-Reihenfolge ab oder legt sie fest. Legt die Anzeigereihenfolge überlappender Signaturen fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Löscht interne Ressourcen |

### Bemerkungen

**Mehr erfahren**

* Grundlegende Verwendung zum Erstellen einer elektronischen Stempelsignatur durch GroupDocs.Signature: [So signieren Sie ein Dokument mit einer Stempelsignatur](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Erweiterte Verwendung der Einstellungen der elektronischen Stempelsignatur mit GroupDocs.Signature: [Erweiterte Nutzung zum eSignieren von Dokumenten mit Stempelsignatur und zusätzlichen Einstellungen](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Siehe auch

* class [ImageSignOptions](../imagesignoptions)
* namensraum [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
