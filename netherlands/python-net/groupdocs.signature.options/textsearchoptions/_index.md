---
title: "TextSearchOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt de zoekopties voor teksthandtekeningen voor."
type: docs
url: /nl/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

Stelt de zoekopties voor teksthandtekeningen voor.

Meer informatie:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

Het TextSearchOptions-type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | Initialiseert een nieuw exemplaar van de TextSearchOptions-klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | Initialiseert een nieuw exemplaar van de TextSearchOptions-klasse met een tekstwaarde. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | Het tekstovereenkomsttype dat wordt gebruikt voor zoeken. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | De implementatie van de teksthandtekening om te zoeken. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | De handtekeningtekst om te matchen tijdens zoeken. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | De vlag die aangeeft of er op elke documentpagina moet worden gezocht. Standaard is deze waarde True. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Het paginanummer van het document voor zoeken (optioneel). (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | De opties om pagina's op te geven voor handtekeningzoeken. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | De vlag die aangeeft of de vormpositie in de documentlay-out moet worden geretourneerd. Alleen beschikbaar voor Word‑documenten. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | De vlag om alleen handtekeningen die gemarkeerd zijn als `IsSignature` te retourneren. Standaard is de waarde `False`, wat aangeeft dat alle handtekeningen die aan de opgegeven criteria voldoen, worden geretourneerd. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Voorbeeld

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
Taakgidsen die `TextSearchOptions` gebruiken:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
