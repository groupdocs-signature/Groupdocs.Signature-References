---
title: "QrCodeSearchOptions‑Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Suchoptionen für QR-Code-Signaturen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Stellt Suchoptionen für QR-Code-Signaturen dar.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

Der QrCodeSearchOptions‑Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit dem Wert für den Kodierungstyp. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit den Werten für Kodierungstyp und Text. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | Die Implementierung von [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) wird verwendet, um QR‑Code‑Signaturtext oder -Dateneigenschaften zu kodieren und zu dekodieren. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | Der Kodierungstyp, nach dem QR‑Codes gesucht werden. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | Der Textabgleichstyp für QR‑Codes, der während der Suche verwendet wird. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | Das Flag, das bestimmt, ob QR‑Code‑Bildinhalt für jede Signatur auf einer Dokumentenseite zurückgegeben wird. Wenn es auf True gesetzt ist, werden die Rohbilddaten in der `content`‑Eigenschaft der Signatur im durch `return_content_type` angegebenen Format gespeichert. Standardmäßig deaktiviert. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | Der Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur, wenn die Eigenschaft `return_content` aktiviert ist. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | Der QR‑Code‑Signaturtext, nach dem gesucht und der abgeglichen werden soll. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Das Flag, das angibt, ob auf jeder Dokumentseite gesucht werden soll. Standardmäßig ist dieser Wert True. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Die Dokumentseitennummer für die Suche (optional). (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Die Optionen, um Seiten für die Signatursuche anzugeben. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Das Flag, das angibt, ob die Position der Form im Dokumentlayout zurückgegeben werden soll. Nur für Word‑Dokumente verfügbar. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Das Flag, um nur Signaturen zurückzugeben, die als `IsSignature` markiert sind. Standardmäßig ist der Wert `False`, was bedeutet, dass alle Signaturen, die den angegebenen Kriterien entsprechen, zurückgegeben werden. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
