---
title: "TextSignOptions‑Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Text‑Signaturoptionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Stellt die Text‑Signaturoptionen dar.

Mehr erfahren

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

Der Typ TextSignOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Initialisiert eine neue Instanz der TextSignOptions‑Klasse mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Initialisiert eine neue Instanz der TextSignOptions‑Klasse mit Text. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Die Hintergrund‑Einstellungen der Signatur. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Die Rahmen‑Einstellungen. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Die Schriftart der Signatur. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Die Vordergrundfarbe der Signatur. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Der Titel des Textformularfeldes, in das die Textsignatur eingefügt werden soll. Kann nur verwendet werden, wenn `signature_implementation` auf `TextSignatureImplementation.FORM_FIELD` gesetzt ist. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Der Typ des Formularfeldes, in das die Textsignatur eingefügt werden soll. Diese Eigenschaft ist nur anwendbar, wenn `signature_implementation` auf `TextSignatureImplementation.FORM_FIELD` (d.h. TextToFormField) gesetzt ist. Der Standardwert ist `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | Die Höhe der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter). Die Einheit wird durch die Eigenschaft `SizeMeasureType` bestimmt. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | Die horizontale Ausrichtung der Signatur auf der Dokumentenseite. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | Die linke X‑Position der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter, wie durch die Eigenschaft `MeasureType` LocationMeasureType definiert). Funktioniert, wenn keine horizontale Ausrichtung angegeben ist. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Der Maßtyp (Pixel, Prozentsätze oder Millimeter) für die Eigenschaften `left` und `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | Der Abstand zwischen der Signatur und den Dokumentkanten. Gilt nur, wenn eine horizontale oder vertikale Ausrichtung angegeben ist. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Der Messtyp (Pixel, Prozente oder Millimeter) für den Rand. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Das native Attribut. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | Der Rotationswinkel der Signatur auf der Dokumentenseite (im Uhrzeigersinn). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Die Formposition definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word‑Dokumente verfügbar. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Der Typ der Form, um Text zu platzieren. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Die eindeutige ID der Signatur, nutzbar in Verifizierungsoptionen und nur für PDF‑Dokumente unterstützt. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Der Typ der Textsignatur-Implementierung. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Der Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | Der Dehnungsmodus auf der Dokumentseite. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Der Text der Signatur. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Die horizontale Ausrichtung des Textes innerhalb einer Signatur, nur für Bild‑ und Annotations‑Signatur‑Implementierungen unterstützt (siehe Eigenschaft `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Die vertikale Ausrichtung des Textes innerhalb einer Signatur. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | Die obere Y‑Position der Signatur auf der Dokumentseite, ausgedrückt in Maßeinheiten (Pixel, Prozent oder Millimeter). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | Die Transparenz der Signatur, ein Gleitkommawert zwischen 0,0 (undurchsichtig) und 1,0 (klar). Standard ist 0,0 (undurchsichtig). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | Die vertikale Ausrichtung der Signatur auf der Dokumentenseite. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | Die Breite der Signatur auf der Dokumentseite in Messwerten (Pixel, Prozentsätze oder Millimeter; siehe Eigenschaft `MeasureType` `SizeMeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Die Signatur wird auf allen Dokumentenseiten platziert. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Das zusätzliche Signatur‑Aussehen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Der Dokumenttyp der Signaturoptionen (`DocumentType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Die Signatur‑Erweiterungen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Der Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Die Dokumentenseitenzahl zum Signieren. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Die Optionen, um die zu signierenden Seiten anzugeben. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Der Signaturtyp (`SignatureType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Die Z‑Reihenfolge‑Position der Textsignatur, die die Anzeigereihenfolge überlappender Signaturen bestimmt. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Aufgabenleitfäden, die `TextSignOptions` verwenden:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
