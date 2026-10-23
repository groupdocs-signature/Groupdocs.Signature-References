---
title: "FormFieldSignOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Formularfeld-Signaturoptionen für PDF-Dokumente dar."
type: docs
url: /de/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

Stellt die Formularfeld-Signaturoptionen für PDF-Dokumente dar.

Stellt Optionen zum Erstellen oder Aktualisieren von Formularfeld‑Signaturen in PDF‑Dateien bereit.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

Der FormFieldSignOptions‑Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | Initialisiert eine neue Instanz der PdfFormFieldSignOptions‑Klasse mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | Initialisiert eine neue Instanz der PdfFormFieldSignOptions‑Klasse mit einer Formularfeld‑Signatur. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | Die Höhe des Signaturbereichs auf der Dokumentseite in Maßeinheiten (Pixel, Prozent oder Millimeter; siehe `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | Die horizontale Ausrichtung des Bildes auf einer Dokumentseite. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | Die linke X‑Position des Signaturbereichs auf der Dokumentseite in Maßeinheiten (Pixel, Prozent oder Millimeter). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Der Maßtyp (Pixel, Prozent oder Millimeter) für die Eigenschaften Left und Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | Der Standardabstand zwischen dem Bild und den Dokumentkanten (gilt, wenn horizontale oder vertikale Ausrichtung festgelegt ist). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | Der Rand‑Messungstyp (Pixel, Prozent oder Millimeter). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | Der Rotationswinkel, im Uhrzeigersinn gemessen. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | Das Formularfeld der Signatur. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Der Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | Der Dehnungsmodus auf der Dokumentseite. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | Die obere Y‑Position des Signaturbereichs auf der Dokumentseite in Maßeinheiten (Pixel, Prozente oder Millimeter). Siehe `MeasureType` für den Standort‑Maßtyp. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | Die Transparenz der Formularfeld‑Signatur. Der Wert liegt zwischen 0,0 und 1,0, standardmäßig 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | Die vertikale Ausrichtung des Bildes auf einer Dokumentseite. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | Die Breite des Signaturbereichs auf der Dokumentseite in Messwerten (Pixel, Prozent oder Millimeter; siehe `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Die Signatur wird auf allen Dokumentenseiten platziert. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Das zusätzliche Signatur‑Aussehen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Die Hintergrundeinstellungen der Signatur. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Die Rahmen-Einstellungen. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Der Dokumenttyp der Signaturoptionen (`DocumentType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Die Signatur‑Erweiterungen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Die Schriftart der Signatur. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Die Vordergrundfarbe der Signatur. (geerbt von [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
