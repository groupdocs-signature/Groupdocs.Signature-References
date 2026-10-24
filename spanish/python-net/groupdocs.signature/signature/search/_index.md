---
title: "método search"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Busca firmas en un documento usando una lista de SearchOptions."
type: docs
url: /es/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Busca firmas en un documento usando una lista de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Aprende más

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | La colección de opciones de búsqueda. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Busca firmas en el documento usando las opciones de búsqueda proporcionadas y filtra los resultados según el predicado especificado.

Más información:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Una lista de instancias de `SearchOptions` que definen los criterios para buscar firmas. |
| predicate | `Func[BaseSignature, bool]` | El predicado de filtro a aplicar sobre la lista de firmas encontradas. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Busque firmas de texto en cada página
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#search_options}

```python
def search(self, search_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Busca tipos de firma especificados en el documento por el valor `SignatureType`.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Uno o varios tipos de firmas para encontrar. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Busque firmas de texto en cada página
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Busca firmas en el documento usando todas las opciones de búsqueda disponibles y filtra los resultados según el predicado especificado.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – una función que recibe un `BaseSignature` y devuelve `True` para mantener la firma o `False` para descartarla. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Buscar firmas de texto y filtrarlas con un predicado personalizado
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
