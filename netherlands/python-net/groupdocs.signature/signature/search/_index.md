---
title: "search methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Zoekt naar handtekeningen in een document met behulp van een lijst met SearchOptions."
type: docs
url: /nl/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Zoekt naar handtekeningen in een document met behulp van een lijst van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Meer informatie

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | De verzameling zoekopties. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Zoekt naar handtekeningen in het document met de opgegeven zoekopties en filtert de resultaten op basis van het gespecificeerde predicaat.

Meer informatie:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Een lijst met `SearchOptions`-instanties die de criteria definiëren voor het zoeken naar handtekeningen. |
| predicate | `Func[BaseSignature, bool]` | De filter‑predicate die moet worden toegepast op de lijst met gevonden handtekeningen. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Zoek naar teksthandtekeningen op elke pagina
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

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Zoekt naar opgegeven handtekeningtypes in het document op basis van de `SignatureType`‑waarde.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Een of meerdere typen handtekeningen om te vinden. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Zoek naar teksthandtekeningen op elke pagina
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Zoekt naar handtekeningen in het document met alle beschikbare zoekopties en filtert de resultaten op basis van het gespecificeerde predicaat.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – een functie die een `BaseSignature` ontvangt en `True` retourneert om de handtekening te behouden of `False` om deze te verwerpen. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Zoek naar teksthandtekeningen en filter ze met een aangepaste predicate.
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
