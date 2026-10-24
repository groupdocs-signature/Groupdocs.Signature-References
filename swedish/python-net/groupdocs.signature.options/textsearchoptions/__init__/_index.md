---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av TextSearchOptions-klassen med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av TextSearchOptions-klassen med standardvärden.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Sök efter textsignaturer med standardalternativ
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Initierar en ny instans av TextSearchOptions-klassen med ett textvärde.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Texten för textsignaturen. |

### Se även
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
