---
title: "SearchResult klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt het resultaat voor van het zoeken naar handtekeningen in een opgegeven document."
type: docs
url: /nl/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Stelt het resultaat voor van het zoeken naar handtekeningen in een opgegeven document.

Het type SearchResult exposeert de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Retourneert een iterator over de zoekresultaten. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | De grootte van het bestemmingsdocument, die altijd 0 is voor de Search-methode. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | De lijst met handtekeningen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) die het zoekproces niet hebben doorstaan volgens de zoekcriteria. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | De uitvoeringstijd van het zoekproces in milliseconden. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | De lijst met gevonden handtekeningen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | De grootte van het brondocument. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | De lijst met gevonden handtekeningen ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Het totale aantal verwerkte handtekeningen dat door het zoekproces wordt geretourneerd. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
