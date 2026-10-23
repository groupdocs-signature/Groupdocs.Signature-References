---
title: "Klasse QrCodeSignature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt QR-Code-Unterschrifts-Eigenschaften dar."
type: docs
url: /de/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

Stellt QR-Code-Unterschrifts-Eigenschaften dar.

Der Typ QrCodeSignature stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | Initialisiert ein QrCodeSignature‑Objekt mit einer Signatur‑Kennung, die nach einem Suchvorgang erhalten wurde. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | Klont die QR‑Code‑Signatur‑Instanz. |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | Bestimmt, ob das gegebene Signatur‑Objekt diesem Objekt gleich ist. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | Überschreibt die GetHashCode-Methode. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | Der binäre Bilddateninhalt des QR‑Codes vom Typ [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | Der QR‑Code‑Kodierungstyp. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | Das Format des QR‑Code‑Signatur‑Bildes. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | Der Text des QR‑Codes. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Das Erstellungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Die Höhe der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Das Flag, das angibt, ob diese Komponente eine Signatur (`True`) oder Dokumentinhalt (`False`) darstellt. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Die linke Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Das Änderungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Die Seitenzahl, auf der die Signatur gefunden wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Der eindeutige Bezeichner der Signatur, der verwendet wird, um die Signatur im Dokument über Update- oder Löschvorgänge zu ändern. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Der Typ der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Die obere Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Die Breite der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
