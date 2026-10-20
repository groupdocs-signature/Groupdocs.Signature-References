---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Stellt die QRCode‑Signaturoptionen dar."
type: docs
weight: 1920
url: /de/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Stellt die Optionen für QR‑Code‑Signaturen dar.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Initialisiert eine neue Instanz der Klasse QRCodeSignOptions mit Standardwerten. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Initialisiert eine neue Instanz der Klasse QRCodeSignOptions mit Text. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Initialisiert eine neue Instanz der BarcodeSignOptions-Klasse mit Text. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Signatur auf allen Dokumentseiten platzieren. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Zusätzliches Signatur‑Erscheinungsbild. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Liest oder legt die Hintergrundeinstellungen der Signatur fest. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Rahmeneinstellungen angeben |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Liest oder legt die Ausrichtung des Textes im resultierenden QR‑Code‑Bild fest. Standardwert ist Keine. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Liest oder legt ein benutzerdefiniertes Objekt fest, das in QR‑Code‑Inhalt serialisiert wird. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Liest oder setzt die Implementierung des [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)-Interfaces zum Codieren und Dekodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Liest oder legt den QR‑Code‑Typ fest. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signatur‑Erweiterungen. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Liest oder legt die Schriftart der Signatur fest. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Liest oder legt die Vordergrundfarbe der QR‑Code‑Balken fest. Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Liest oder legt den Titel des Textformularfelds fest, in das die Textsignatur eingefügt wird. Diese Eigenschaft kann nur zusammen mit SignatureImplementation = TextToFormField verwendet werden. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Liest oder legt den Typ des Formularfelds fest, in das die Textsignatur eingefügt wird. Diese Eigenschaft kann nur zusammen mit SignatureImplementation = TextToFormField verwendet werden. Der Standardwert ist AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Liest oder legt den Hash‑Algorithmus fest, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType‑Eigenschaft). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontale Ausrichtung der Signatur auf der Dokumentseite. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Liest oder legt den Abstand zwischen QR‑Code‑Elementen und den Rändern des Ergebnisbildes fest. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Linke X‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType‑Eigenschaft). (funktioniert, wenn keine horizontale Ausrichtung angegeben ist). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Left und Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Liest oder legt den Dateinamen des QR‑Code‑Logo‑Bildes fest. Diese Eigenschaft wird nur verwendet, wenn LogoStream nicht angegeben ist. Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Liest oder legt den Bildstrom des QR‑Code‑Logos fest. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von LogoFilePath verwendet. Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Liest oder legt den Abstand zwischen Signatur und Dokumentkanten fest. (funktioniert NUR, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Liest oder legt den Messwerttyp (Pixel, Prozentsätze oder Millimeter) für den Rand fest. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Liest oder legt das native Attribut fest. Wenn es gesetzt ist, können dokumentspezifische Signaturen verwendet werden. Das native Textwasserzeichen für WordProcessing-Dokumente unterscheidet sich beispielsweise vom regulären. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Liest oder legt die Dokumentseitennummer für die Signatur fest. Minimaler und Standardwert ist 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Optionen zum Angeben der zu signierenden Seiten. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Liest oder legt das Flag fest, um den QR‑Code‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentseite platziert wurde. Wenn dieses Flag auf true gesetzt ist, behält der QR‑Code‑Signatur‑Bildinhalt die Rohbilddaten im erforderlichen Format [`ReturnContentType`](./returncontenttype). Standardmäßig ist diese Option deaktiviert. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Gibt den Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. Standardmäßig ist er auf Null gesetzt. Das bedeutet, dass der QR‑Code‑Bildinhalt im Originalformat zurückgegeben wird. Dieses Bildformat wird bei [`Format`](../../groupdocs.signature.domain/qrcodesignature/format) angegeben. Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der QR‑Code‑Bildinhalt im .png‑Format zurückgegeben. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotationswinkel der Signatur auf der Dokumentseite (im Uhrzeigersinn). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word‑Dokumente verfügbar. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Liest oder legt den Typ der Form fest, in die Text eingefügt wird. Diese Eigenschaft kann nur zusammen mit SignatureImplementation = TextStamp verwendet werden. Der Standardwert ist Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Liest oder legt die eindeutige ID der Signatur fest. Sie kann in den Optionen zur Signaturüberprüfung verwendet werden. Die Eigenschaft wird nur für Pdf‑Dokumente unterstützt. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Liest oder legt den Typ der Textsignatur‑Implementierung fest. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Abrufen des Signaturtyps [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Dehnungsmodus auf der Dokumentseite. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Liest oder legt den Text der Signatur fest. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Horizontale Ausrichtung des Textes innerhalb einer Signatur. Diese Funktion wird nur für Bild- und Anmerkungs‑Signaturimplementierungen unterstützt (siehe [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation‑Eigenschaft). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Vertikale Ausrichtung des Textes innerhalb einer Signatur. Diese Funktion wird nur für Bild‑Signaturimplementierungen unterstützt (siehe [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation‑Eigenschaft). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Obere Y‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozente oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType‑Eigenschaft). (funktioniert, wenn die vertikale Ausrichtung nicht angegeben ist). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Liest oder setzt die Transparenz der Signatur (Wert von 0,0 (undurchsichtig) bis 1,0 (transparent)). Standardwert ist 0 (undurchsichtig). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Vertikale Ausrichtung der Signatur auf der Dokumentseite. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozente oder Millimeter, siehe [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType‑Eigenschaft). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Liest oder setzt die Z‑Reihenfolge‑Position der Textsignatur. Bestimmt die Anzeigereihenfolge überlappender Signaturen. |

### Hinweise

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Siehe auch

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
