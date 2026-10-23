---
title: "BarcodeSignOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Barcode-Signaturoptionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Stellt die Barcode-Signaturoptionen dar.

Mehr erfahren

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

Der Typ BarcodeSignOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | Die Ausrichtung des Textes im resultierenden Barcode-Bild. Standardwert ist None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | Der Barcode-Typ. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | Die Vordergrundfarbe der Barcode-Streifen; deren Verwendung kann zu Verifizierungsproblemen führen, daher vorsichtig einsetzen. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | Die Höhe des Signaturbereichs auf der Dokumentenseite in Maßeinheiten (Pixel, Prozent oder Millimeter). Siehe `MeasureType` für den Größeneinheitstyp. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | Die horizontale Ausrichtung des Bildes auf einer Dokumentseite. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | Der Abstand zwischen Barcode-Elementen und den Rändern des Ergebnisbildes. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | Die linke X-Position des Signaturbereichs auf der Dokumentenseite, angegeben in Maßeinheiten (Pixel, Prozent oder Millimeter). Siehe `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | Der Messtyp (Pixel, Prozente oder Millimeter) für die linken und oberen Eigenschaften. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | Der standardmäßig zwischen dem Bild und den Dokumenträndern angegebene Abstand (gilt, wenn horizontale oder vertikale Ausrichtung festgelegt ist). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | Der Messungstyp für den Rand (Pixel, Prozente oder Millimeter). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | Das Flag, das angibt, ob der Barcode-Bildinhalt einer auf einer Dokumentenseite platzierten Signatur abgerufen werden soll. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | Der Dateityp des zurückgegebenen Bildinhalts der Barcode-Signatur, wenn die Eigenschaft `return_content` aktiviert ist. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | Der Rotationswinkel im Uhrzeigersinn. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Der Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | Der Dehnungsmodus auf der Dokumentenseite. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | Die obere Y-Position des Signaturbereichs auf der Dokumentenseite in Maßeinheiten (Pixel, Prozent oder Millimeter). Siehe `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | Die Transparenz der Barcode-Signatur, von 0,0 (vollständig undurchsichtig) bis 1,0 (vollständig transparent); Standardwert ist 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | Die vertikale Ausrichtung des Barcode-Bildes auf einer Dokumentenseite. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | Die Breite des Signaturbereichs auf der Dokumentenseite in Messwerten (Pixel, Prozent oder Millimeter) wie durch `MeasureType` definiert. |
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
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Aufgabenleitfäden, die `BarcodeSignOptions` verwenden:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
