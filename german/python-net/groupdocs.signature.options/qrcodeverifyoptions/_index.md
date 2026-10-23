---
title: "QrCodeVerifyOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Enthält Optionen zur Überprüfung der QR-Code-Signatur des Dokuments."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

Enthält Optionen zur Überprüfung der QR-Code-Signatur des Dokuments.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

Der QrCodeVerifyOptions-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | Initialisiert Verifizierungsoptionen für QR-Code‑Signaturen. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | Initialisiert Verifizierungsoptionen für QR-Code‑Signaturen mit dem angegebenen QR-Code‑Text. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | Initialisiert Verifizierungsoptionen für QR-Code‑Signaturen mit Text und QR-Code‑Kodierungstyp zur Verifizierung. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | Die Implementierung von [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) wird verwendet, um QR-Code‑Signatur‑Texteigenschaften zu kodieren und zu dekodieren. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | Die QR-Code‑Typ‑Verifizierung. Diese Eigenschaft ist optional. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Das Flag gibt an, ob jede Dokumentseite verifiziert werden soll. Standardmäßig ist der Wert True. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Die zusätzlichen Erweiterungen für die Verifizierung alternativer Signaturoptionen. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Der Titel des zu überprüfenden Formularfelds. Wenn gesetzt, wird der Text nur in Text‑Formularfeldern gefunden. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Der Typ des zu überprüfenden Formularfelds; wenn gesetzt, wird der Text nur in Text‑Formularfeldern gefunden. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Das gültige Eigenschafts‑Flag. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Die Verifizierung des Text‑Übereinstimmungstyps. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Die zu verifizierende Dokumentseitennummer; wenn nicht festgelegt, werden alle Seiten des Dokuments für das erste Vorkommen verifiziert (Mindestwert ist 1). (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Die Seitenoptionen zur Angabe der zu verifizierenden Seiten. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Die Formposition im Dokumentlayout, die zum Verifizieren von Signaturen in Kopf‑/Fußzeilen verwendet wird. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Die Text‑Signatur‑ID zur Verifizierung. Muss größer als Null sein; wird nur für PDF‑Dokumente unterstützt. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Der Typ der zu verifizierenden Signatur. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Der zu verifizierende Signaturtext. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
