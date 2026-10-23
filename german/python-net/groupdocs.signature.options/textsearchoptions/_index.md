---
title: "Klasse TextSearchOptions"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Suchoptionen für Text‑Signaturen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

Stellt Suchoptionen für Text‑Signaturen dar.

Mehr erfahren:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

Der Typ TextSearchOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | Initialisiert eine neue Instanz der Klasse TextSearchOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | Initialisiert eine neue Instanz der Klasse TextSearchOptions mit einem Textwert. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | Der für die Suche verwendete Textübereinstimmungstyp. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | Die zu suchende Textsignatur-Implementierung. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | Der Signaturtext, der bei der Suche übereinstimmen soll. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Das Flag, das angibt, ob auf jeder Dokumentseite gesucht werden soll. Standardmäßig ist dieser Wert True. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Die Dokumentseitennummer für die Suche (optional). (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Die Optionen, um Seiten für die Signatursuche anzugeben. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Das Flag, das angibt, ob die Position der Form im Dokumentlayout zurückgegeben werden soll. Nur für Word‑Dokumente verfügbar. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Das Flag, um nur Signaturen zurückzugeben, die als `IsSignature` markiert sind. Standardmäßig ist der Wert `False`, was bedeutet, dass alle Signaturen, die den angegebenen Kriterien entsprechen, zurückgegeben werden. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
Aufgabenleitfäden, die `TextSearchOptions` verwenden:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
