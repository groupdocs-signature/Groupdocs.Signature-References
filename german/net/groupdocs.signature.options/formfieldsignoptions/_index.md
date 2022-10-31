---
title: FormFieldSignOptions
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Repräsentiert die Klasse der FormFieldSignaturoptionen für PDFDokumente.
type: docs
weight: 1300
url: /de/net/groupdocs.signature.options/formfieldsignoptions/
---
## FormFieldSignOptions class

Repräsentiert die Klasse der FormField-Signaturoptionen für PDF-Dokumente.

```csharp
public sealed class FormFieldSignOptions : TextSignOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FormFieldSignOptions](formfieldsignoptions#constructor)() | Initialisiert eine neue Instanz der PdfFormFieldSignOptions-Klasse mit Standardwerten. |
| [FormFieldSignOptions](formfieldsignoptions#constructor_1)(FormFieldSignature) | Initialisiert eine neue Instanz der PdfFormFieldSignOptions-Klasse mit FormField-Signatur. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Unterschreiben Sie alle Dokumentseiten. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Zusätzliche Signaturdarstellung. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Ruft die Hintergrundeinstellungen der Signatur ab oder legt sie fest. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Rahmeneinstellungen festlegen |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signaturerweiterungen. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Ruft die Schriftart der Signatur ab oder legt sie fest. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Ruft die Vordergrundfarbe der Signatur ab oder setzt sie. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Ruft den Titel des Textformularfelds ab oder legt ihn fest, um eine Textsignatur darin einzufügen. Diese Eigenschaft kann nur mit SignatureImplementation = TextToFormField verwendet werden. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Ruft den Typ des Formularfelds ab oder legt ihn fest, um eine Textsignatur darin einzufügen. Diese Eigenschaft kann nur mit SignatureImplementation = TextToFormField verwendet werden. Der Standardwert ist AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Höhe der Unterschrift auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter s[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType-Eigenschaft). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontale Ausrichtung der Signatur auf der Dokumentenseite. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Linke X-Position der Signatur auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter siehe[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType-Eigenschaft). (funktioniert, wenn keine horizontale Ausrichtung angegeben ist). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Maßtyp (Pixel, Prozent oder Millimeter) für Left- und Top-Eigenschaften. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Ruft den Abstand zwischen Zeichen- und Dokumentkanten ab oder legt ihn fest. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Ruft den Maßtyp (Pixel, Prozent oder Millimeter) für den Rand ab oder legt ihn fest. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Ruft das native Attribut ab oder legt es fest. Wenn es eingestellt ist, können dokumentspezifische Signaturen verwendet werden. Natives Textwasserzeichen für WordProcessing-Dokumente ist beispielsweise anders als normal. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ruft die Seitenzahl des Dokuments zum Signieren ab oder legt sie fest. Minimal- und Standardwert ist 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Optionen zum Angeben von Seiten, die signiert werden sollen. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotationswinkel der Unterschrift auf der Dokumentenseite (im Uhrzeigersinn). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Ruft den Typ der Form zum Einfügen von Text ab oder legt ihn fest. Diese Eigenschaft kann nur mit SignatureImplementation = TextStamp verwendet werden. Der Standardwert ist Rectangle. |
| [Signature](../../groupdocs.signature.options/formfieldsignoptions/signature) { get; set; } | Ruft das FormField der Signatur ab oder legt es fest. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Ruft die eindeutige ID der Signatur ab oder legt sie fest. Es kann in Optionen zur Signaturüberprüfung verwendet werden. Eigenschaft wird nur für PDF-Dokumente unterstützt. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Ruft den Typ der Textsignaturimplementierung ab oder legt ihn fest. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Holen Sie sich den Signaturtyp[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Maßtyp (Pixel, Prozent oder Millimeter) für Breiten- und Höheneigenschaften. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Dehnungsmodus auf Dokumentseite. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Ruft den Signaturtext ab oder legt ihn fest. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Horizontale Ausrichtung von Text innerhalb einer Signatur. Diese Funktion wird nur für Bild- und Anmerkungssignaturimplementierungen unterstützt (siehe[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation-Eigenschaft). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Vertikale Ausrichtung von Text innerhalb einer Signatur. Diese Funktion wird nur für die Bildsignaturimplementierung unterstützt (siehe[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation-Eigenschaft). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Top Y Position der Unterschrift auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter s[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType-Eigenschaft). (funktioniert, wenn keine vertikale Ausrichtung angegeben ist). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Holt oder setzt die Signaturtransparenz (Wert von 0,0 (undurchsichtig) bis 1,0 (klar)). Der Standardwert ist 0 (undurchsichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Vertikale Ausrichtung der Signatur auf der Dokumentenseite. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Breite der Signatur auf Dokumentseite in Messwerte (Pixel, Prozent oder Millimeter s[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType-Eigenschaft). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ruft die Position der Textsignatur in Z-Reihenfolge ab oder legt sie fest. Legt die Anzeigereihenfolge überlappender Signaturen fest. |

### Bemerkungen

**Mehr erfahren**

* Grundlegende Verwendung zum Erstellen einer elektronischen FormField-Signatur durch GroupDocs.Signature: [So signieren Sie ein Dokument mit einer FormField-Signatur](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature)
* Erweiterte Nutzung der Einstellungen der elektronischen Signatur FormField mit GroupDocs.Signature: [Erweiterte Nutzung zum eSignieren von Dokumenten mit FormField-Signatur und zusätzlichen Einstellungen](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced)

### Siehe auch

* class [TextSignOptions](../textsignoptions)
* namensraum [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
