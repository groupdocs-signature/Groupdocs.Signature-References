---
title: search method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Searches for signatures in a document using a list of SearchOptions."
type: docs
url: /python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Searches for signatures in a document using a list of [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Learn more

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | The search options collection. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Searches for signatures in the document using the provided search options and filters the results based on the specified predicate.

Learn more:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | A list of `SearchOptions` instances defining the criteria for searching signatures. |
| predicate | `Func[BaseSignature, bool]` | The filter predicate to apply on the list of found signatures. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Look for text signatures on every page
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

| Parameter | Type | Description |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Searches for specified signature types in the document by `SignatureType` value.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | One or several types of signatures to find. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Look for text signatures on every page
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Searches for signatures in the document using all available search options and filters the results based on the specified predicate.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – a function that receives a `BaseSignature` and returns `True` to keep the signature or `False` to discard it. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Search for text signatures and filter them with a custom predicate
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### See Also
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
