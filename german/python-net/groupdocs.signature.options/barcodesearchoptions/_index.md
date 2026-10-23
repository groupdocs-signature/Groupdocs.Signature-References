---
title: "BarcodeSearchOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Suchoptionen für Barcode-Signaturen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

Stellt Suchoptionen für Barcode-Signaturen dar.

Mehr erfahren:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

Der Typ BarcodeSearchOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | Initialisiert eine neue Instanz der BarcodeSearchOptions Klasse mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | Initialisiert eine neue Instanz der BarcodeSearchOptions Klasse mit dem Encode-Typ-Wert. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | Initialisiert eine neue Instanz der BarcodeSearchOptions Klasse mit Encode-Typ- und Textwerten. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | Der Encode-Typ, der zur Filterung der Barcode-Suche verwendet wird; wenn nicht festgelegt, umfasst die Suche alle unterstützten Barcode-Typen. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | Der Barcode-Textübereinstimmungstyp, der für die Suche verwendet wird. Er wird nur verwendet, wenn die `text`-Eigenschaft gesetzt ist. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | Das Flag, das angibt, ob der Barcode-Bildinhalt einer Signatur auf einer Dokumentseite abgerufen werden soll. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | Der Dateityp des zurückgegebenen Bildinhalts für eine Barcode-Signatur, wenn die `return_content`-Eigenschaft aktiviert ist. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | Der Text der Barcode-Signatur, nach dem gesucht und der abgeglichen werden soll. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Das Flag, das angibt, ob auf jeder Dokumentseite gesucht werden soll. Standardmäßig ist dieser Wert True. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Die Dokumentseitennummer für die Suche (optional). (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Die Optionen, um Seiten für die Signatursuche anzugeben. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Das Flag, das angibt, ob die Position der Form im Dokumentlayout zurückgegeben werden soll. Nur für Word‑Dokumente verfügbar. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Das Flag, um nur Signaturen zurückzugeben, die als `IsSignature` markiert sind. Standardmäßig ist der Wert `False`, was bedeutet, dass alle Signaturen, die den angegebenen Kriterien entsprechen, zurückgegeben werden. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
Aufgabenleitfäden, die `BarcodeSearchOptions` verwenden:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
