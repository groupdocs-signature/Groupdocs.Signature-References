---
title: "TextVerifyOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Enthält Optionen zur Überprüfung der Text‑Signatur eines Dokuments."
type: docs
url: /de/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Enthält Optionen zur Überprüfung der Text‑Signatur eines Dokuments.

Mehr erfahren:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

Der TextVerifyOptions‑Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | Initialisiert eine neue Instanz von TextVerifyOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | Initialisiert eine neue Instanz von TextVerifyOptions mit dem zu überprüfenden Text. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Initialisiert eine neue TextVerifyOptions‑Instanz mit dem zu überprüfenden Text und dem Signatur‑Implementierungstyp. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Der Titel des zu überprüfenden Formularfelds. Wenn festgelegt, wird der Text nur in Textformularfeldern gefunden. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Der Typ des zu überprüfenden Formularfelds; wenn festgelegt, wird der Text nur in Textformularfeldern gefunden. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Die Überprüfung des Textübereinstimmungstyps. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Die Textsignatur-ID zur Überprüfung. Muss größer als Null sein; wird nur für PDF-Dokumente unterstützt. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Der zu überprüfende Signaturtyp. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Der zu überprüfende Signaturtext. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Das Flag gibt an, ob jede Dokumentseite verifiziert werden soll. Standardmäßig ist der Wert True. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Die zusätzlichen Erweiterungen für die Verifizierung alternativer Signaturoptionen. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Das gültige Eigenschafts‑Flag. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Die zu verifizierende Dokumentseitennummer; wenn nicht festgelegt, werden alle Seiten des Dokuments für das erste Vorkommen verifiziert (Mindestwert ist 1). (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Die Seitenoptionen zur Angabe der zu verifizierenden Seiten. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Die Formposition im Dokumentlayout, die zum Verifizieren von Signaturen in Kopf‑/Fußzeilen verwendet wird. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
Aufgabenleitfäden, die `TextVerifyOptions` verwenden:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
