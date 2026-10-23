---
title: "Klasse QrCodeSignOptions"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die QR-Code-Signatur-Optionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Stellt die QR-Code-Signatur-Optionen dar.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

Der QrCodeSignOptions-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Initialisiert eine neue Instanz der QRCodeSignOptions-Klasse mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Initialisiert eine QR-Code-Signaturoptions-Instanz mit dem angegebenen Text. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Initialisiert eine neue Instanz der QrCodeSignOptions-Klasse mit Text. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | Die Ausrichtung des Textes im resultierenden QR-Code-Bild, der Standardwert ist None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | Das benutzerdefinierte Objekt, das in QR-Code-Inhalt serialisiert werden soll. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | Die Datenverschlüsselungsimplementierung, die zum Codieren und Dekodieren von QR-Code-Signaturtext oder -daten verwendet wird. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | Der QR-Code-Typ. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | Die Vordergrundfarbe der QR-Code-Balken; die Verwendung dieser Eigenschaft kann Verifizierungsprobleme verursachen, daher vorsichtig einsetzen. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | Die Höhe des Signaturbereichs auf der Dokumentseite in Maßeinheiten (Pixel, Prozent oder Millimeter; siehe `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | Die horizontale Ausrichtung des QR-Codes auf einer Dokumentseite. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | Der Abstand zwischen QR-Code-Elementen und den Rändern des Ergebnisbildes. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | Die linke X-Position des Signaturbereichs auf einer Dokumentseite in Maßeinheiten (Pixel, Prozent oder Millimeter). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Der Messtyp (Pixel, Prozente oder Millimeter) für die linken und oberen Eigenschaften. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | Der Dateiname des QR-Code-Logo-Bildes. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | Der QR-Code-Logo-Bild-Stream. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | Der standardmäßig angegebene Abstand zwischen Bild- und Dokumentkanten (funktioniert, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Der Messungstyp für den Rand (Pixel, Prozente oder Millimeter). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | Das Flag zum Abrufen des QR-Code-Bildinhalts einer auf einer Dokumentseite platzierten Signatur. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | Der Dateityp des zurückgegebenen Bildinhalts der QR‑Code-Signatur, wenn die Eigenschaft `return_content` aktiviert ist. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | Der Rotationswinkel in Grad, im Uhrzeigersinn. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Der Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | Der Dehnungsmodus auf der Dokumentenseite. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | Die obere Y-Position des Signaturbereichs auf einer Dokumentseite in Maßeinheiten (Pixel, Prozent oder Millimeter). Die Einheit wird durch die Eigenschaft `LocationMeasureType` vom Typ `MeasureType` definiert. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | Die Transparenz der QR-Code-Signatur. Der Wert liegt zwischen 0,0 und 1,0, standardmäßig 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | Die vertikale Ausrichtung des Bildes auf einer Dokumentseite. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | Die Breite des Signaturbereichs auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter, wie durch `MeasureType` definiert). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Die Signatur wird auf allen Dokumentenseiten platziert. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Das zusätzliche Signatur‑Aussehen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Die Hintergrundeinstellungen der Signatur. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Die Rahmen-Einstellungen. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Der Dokumenttyp der Signaturoptionen (`DocumentType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Die Signatur‑Erweiterungen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Die Schriftart der Signatur. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Der Titel des Textformularfelds, in das die Textsignatur eingefügt werden soll. Kann nur verwendet werden, wenn `signature_implementation` auf `TextSignatureImplementation.FORM_FIELD` gesetzt ist. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Der Typ des Formularfelds, in das die Textsignatur eingefügt werden soll. Diese Eigenschaft ist nur anwendbar, wenn `signature_implementation` auf `TextSignatureImplementation.FORM_FIELD` (d.h. TextToFormField) gesetzt ist. Der Standardwert ist `FormTextFieldType.ALL_TEXT_TYPES`. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Der Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Das native Attribut. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Die Dokumentenseitenzahl zum Signieren. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Die Optionen, um die zu signierenden Seiten anzugeben. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Die Position der Form definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word-Dokumente verfügbar. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Der Typ der Form, um Text zu platzieren. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Die eindeutige ID der Signatur, die in Verifizierungsoptionen verwendet werden kann und nur für PDF-Dokumente unterstützt wird. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Der Typ der Textsignatur-Implementierung. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Der Signaturtyp (`SignatureType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Der Text der Signatur. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Die horizontale Ausrichtung des Textes innerhalb einer Signatur, unterstützt nur für Bild- und Annotations‑Signatur‑Implementierungen (siehe `TextSignatureImplementation` SignatureImplementation). (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Die vertikale Ausrichtung des Textes innerhalb einer Signatur. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Die Z‑Reihenfolge‑Position der Textsignatur, die die Anzeigereihenfolge überlappender Signaturen bestimmt. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Übergeben Sie den Text und den QR-Code-Typ an den Konstruktor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Platzieren Sie den QR-Code in der unteren rechten Ecke der Seite
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Modulfarbe, Hintergrund und ein gepunkteter Rand mit etwas Abstand innen
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
Aufgabenleitfäden, die `QrCodeSignOptions` verwenden:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
