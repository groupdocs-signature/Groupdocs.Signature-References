---
title: "SearchResult-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar resultatet av sökning efter signaturer i ett specificerat dokument."
type: docs
url: /sv/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Representerar resultatet av sökning efter signaturer i ett specificerat dokument.

SearchResult-typen exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Returnerar en iterator över sökresultaten. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Destinationsdokumentets storlek, som alltid är 0 för Search-metoden. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | Listan över signaturer [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) som misslyckades med sökprocessen enligt sökkriterier. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Exekveringstiden för sökprocessen i millisekunder. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | Listan över hittade signaturer [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | Källdokumentets storlek. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | Listan över hittade signaturer ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Det totala antalet bearbetade signaturer som returnerats av sökprocessen. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
