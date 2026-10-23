---
title: "méthode search"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Recherche des signatures dans un document en utilisant une liste de SearchOptions."
type: docs
url: /fr/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Recherche des signatures dans un document en utilisant une liste de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

En savoir plus

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | La collection d'options de recherche. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Recherche des signatures dans le document en utilisant les options de recherche fournies et filtre les résultats selon le prédicat spécifié.

En savoir plus :
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Une liste d'instances `SearchOptions` définissant les critères de recherche des signatures. |
| predicate | `Func[BaseSignature, bool]` | Le prédicat de filtre à appliquer sur la liste des signatures trouvées. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Recherchez les signatures texte sur chaque page
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

| Paramètre | Type | Description |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Recherche les types de signature spécifiés dans le document par la valeur `SignatureType`.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Un ou plusieurs types de signatures à trouver. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Recherchez les signatures texte sur chaque page
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Recherche des signatures dans le document en utilisant toutes les options de recherche disponibles et filtre les résultats selon le prédicat spécifié.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – une fonction qui reçoit un `BaseSignature` et renvoie `True` pour conserver la signature ou `False` pour la rejeter. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Rechercher des signatures texte et les filtrer avec un prédicat personnalisé
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
