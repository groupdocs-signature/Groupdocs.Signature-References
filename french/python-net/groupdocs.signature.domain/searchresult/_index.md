---
title: "Classe SearchResult"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente le résultat de la recherche de signatures dans un document spécifié."
type: docs
url: /fr/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Représente le résultat de la recherche de signatures dans un document spécifié.

Le type SearchResult expose les membres suivants:

### Méthodes
| Méthode | Description |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Renvoie un itérateur sur les résultats de recherche. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | La taille du document de destination, qui est toujours 0 pour la méthode Search. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | La liste des signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) qui ont échoué le processus de recherche selon les critères de recherche. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Le temps d'exécution du processus de recherche en millisecondes. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | La liste des signatures trouvées [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | La taille du document source. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | La liste des signatures trouvées ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Le nombre total de signatures traitées renvoyées par le processus de recherche. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
