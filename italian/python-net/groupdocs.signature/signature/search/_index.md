---
title: "metodo search"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Cerca firme in un documento utilizzando un elenco di SearchOptions."
type: docs
url: /it/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Cerca firme in un documento utilizzando un elenco di [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Maggiori informazioni

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | La collezione delle opzioni di ricerca. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Cerca firme nel documento utilizzando le opzioni di ricerca fornite e filtra i risultati in base al predicato specificato.

Per saperne di più:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Un elenco di istanze `SearchOptions` che definiscono i criteri per la ricerca delle firme. |
| predicate | `Func[BaseSignature, bool]` | Il predicato di filtro da applicare all'elenco delle firme trovate. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Cerca firme di testo in ogni pagina
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

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Cerca i tipi di firma specificati nel documento per valore `SignatureType`.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Uno o più tipi di firme da trovare. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Cerca firme di testo in ogni pagina
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Cerca firme nel documento utilizzando tutte le opzioni di ricerca disponibili e filtra i risultati in base al predicato specificato.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – una funzione che riceve un `BaseSignature` e restituisce `True` per mantenere la firma o `False` per scartarla. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Cerca firme di testo e filtrale con un predicato personalizzato.
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
