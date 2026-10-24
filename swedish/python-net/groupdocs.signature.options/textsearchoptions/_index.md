---
title: "TextSearchOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar sökalternativ för Textsignaturer."
type: docs
url: /sv/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

Representerar sökalternativ för Textsignaturer.

Läs mer:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

TextSearchOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | Initierar en ny instans av TextSearchOptions-klassen med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | Initierar en ny instans av TextSearchOptions-klassen med ett textvärde. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | Textmatchningstypen som används för sökning. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | Textsignaturimplementeringen att söka efter. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | Signaturtexten att matcha vid sökning. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Flaggan som anger om varje dokumentsida ska genomsökas. Standardvärdet är True. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Dokumentsidans nummer för sökning (valfritt). (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Alternativen för att ange sidor för signatursökning. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Flaggan som anger om formens position i dokumentlayouten ska returneras. Endast tillgänglig för Word‑dokument. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Flaggan för att endast returnera signaturer markerade som `IsSignature`. Standardvärdet är `False`, vilket innebär att alla signaturer som matchar de angivna kriterierna returneras. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exempel

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
Uppgiftsguider som använder `TextSearchOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
