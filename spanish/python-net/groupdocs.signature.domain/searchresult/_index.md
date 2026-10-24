---
title: "Clase SearchResult"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa el resultado de la búsqueda de firmas en un documento especificado."
type: docs
url: /es/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Representa el resultado de la búsqueda de firmas en un documento especificado.

El tipo SearchResult expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Devuelve un iterador sobre los resultados de la búsqueda. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | El tamaño del documento de destino, que siempre es 0 para el método Search. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | La lista de firmas [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) que fallaron el proceso de búsqueda por criterios de búsqueda. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | El tiempo de ejecución del proceso de búsqueda en milisegundos. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | La lista de firmas encontradas [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | El tamaño del documento de origen. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | La lista de firmas encontradas ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | El número total de firmas procesadas devuelto por el proceso de búsqueda. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
