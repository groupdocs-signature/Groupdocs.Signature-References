---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse TextSearchOptions mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der Klasse TextSearchOptions mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Suche nach Textsignaturen mit den Standardoptionen
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Initialisiert eine neue Instanz der Klasse TextSearchOptions mit einem Textwert.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Text der Textsignatur. |

### Siehe auch
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
