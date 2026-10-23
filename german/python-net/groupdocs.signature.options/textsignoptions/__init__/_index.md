---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der TextSignOptions‑Klasse mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der TextSignOptions‑Klasse mit Standardwerten.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialisiert eine neue Instanz der TextSignOptions‑Klasse mit Text.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Signaturtext. |

### Beispiel

```python
from groupdocs.signature.options import TextSignOptions

# Erstellen Sie eine Textsignatur‑Option mit dem gewünschten Signaturtext.
options = TextSignOptions("John Smith")
```

### Siehe auch
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
