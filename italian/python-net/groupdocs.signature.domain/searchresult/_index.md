---
title: "Classe SearchResult"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta il risultato della ricerca di firme in un documento specificato."
type: docs
url: /it/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Rappresenta il risultato della ricerca di firme in un documento specificato.

Il tipo SearchResult espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Restituisce un iteratore sui risultati della ricerca. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | La dimensione del documento di destinazione, che è sempre 0 per il metodo Search. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | L'elenco delle firme [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) che non hanno superato il processo di ricerca secondo i criteri di ricerca. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Il tempo di esecuzione del processo di ricerca in millisecondi. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | L'elenco delle firme trovate [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | La dimensione del documento di origine. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | L'elenco delle firme trovate ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Il numero totale di firme elaborate restituite dal processo di ricerca. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
