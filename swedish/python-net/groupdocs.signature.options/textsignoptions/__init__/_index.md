---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av TextSignOptions‑klassen med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av TextSignOptions‑klassen med standardvärden.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initierar en ny instans av TextSignOptions‑klassen med text.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Signaturtext. |

### Exempel

```python
from groupdocs.signature.options import TextSignOptions

# Skapa ett textsignaturalternativ med önskad signaturtext
options = TextSignOptions("John Smith")
```

### Se även
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
