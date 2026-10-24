---
title: "search metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Söker efter signaturer i ett dokument med hjälp av en lista med SearchOptions."
type: docs
url: /sv/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Söker efter signaturer i ett dokument med hjälp av en lista med [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Läs mer

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Sökalternativsamlingen. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Söker efter signaturer i dokumentet med de angivna sökalternativen och filtrerar resultaten baserat på det angivna predikatet.

Läs mer:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | En lista med `SearchOptions`‑instanser som definierar kriterierna för att söka signaturer. |
| predicate | `Func[BaseSignature, bool]` | Filterpredikatet att tillämpa på listan med hittade signaturer. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Sök efter textsignaturer på varje sida.
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

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Söker efter angivna signaturtyper i dokumentet efter `SignatureType`‑värde.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | En eller flera typer av signaturer att hitta. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Sök efter textsignaturer på varje sida.
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Söker efter signaturer i dokumentet med alla tillgängliga sökalternativ och filtrerar resultaten baserat på det angivna predikatet.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – en funktion som tar emot en `BaseSignature` och returnerar `True` för att behålla signaturen eller `False` för att förkasta den. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Sök efter textsignaturer och filtrera dem med ett anpassat predikat
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
