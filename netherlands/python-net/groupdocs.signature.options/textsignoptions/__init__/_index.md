---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de TextSignOptions klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de TextSignOptions klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialiseert een nieuw exemplaar van de TextSignOptions klasse met tekst.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Handtekeningtekst. |

### Voorbeeld

```python
from groupdocs.signature.options import TextSignOptions

# Maak een teksthandtekeningoptie met de gewenste handtekeningtekst
options = TextSignOptions("John Smith")
```

### Zie ook
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
