---
title: "search Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Durchsucht ein Dokument nach Signaturen mithilfe einer Liste von SearchOptions."
type: docs
url: /de/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Sucht nach Signaturen in einem Dokument mithilfe einer Liste von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Mehr erfahren

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Die Sammlung der Suchoptionen. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Sucht nach Signaturen im Dokument unter Verwendung der bereitgestellten Suchoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat.

Mehr erfahren:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Eine Liste von `SearchOptions`-Instanzen, die die Kriterien für die Suche nach Signaturen definieren. |
| predicate | `Func[BaseSignature, bool]` | Das Filterprädikat, das auf die Liste gefundener Signaturen angewendet wird. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Suchen Sie nach Textsignaturen auf jeder Seite.
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

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Sucht nach angegebenen Signaturtypen im Dokument anhand des `SignatureType`-Werts.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Ein oder mehrere Typen von Signaturen, die gefunden werden sollen. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Suchen Sie nach Textsignaturen auf jeder Seite.
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Sucht nach Signaturen im Dokument unter Verwendung aller verfügbaren Suchoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – eine Funktion, die ein `BaseSignature` erhält und `True` zurückgibt, um die Signatur zu behalten, oder `False`, um sie zu verwerfen. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Suche nach Textsignaturen und filtere sie mit einem benutzerdefinierten Prädikat
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
