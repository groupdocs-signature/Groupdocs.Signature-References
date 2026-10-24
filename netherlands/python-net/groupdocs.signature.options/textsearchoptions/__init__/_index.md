---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de TextSearchOptions-klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de TextSearchOptions-klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Zoek naar teksthandtekeningen met behulp van standaardopties
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Initialiseert een nieuw exemplaar van de TextSearchOptions-klasse met een tekstwaarde.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Tekst van de teksthandtekening. |

### Zie ook
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
