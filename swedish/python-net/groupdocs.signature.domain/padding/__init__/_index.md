---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av Padding‑klassen med nollvärden."
type: docs
url: /sv/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av Padding‑klassen med nollvärden.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature.domain import Padding

# Skapa ett utfyllnadsobjekt med standardvärden (noll)
default_padding = Padding()
```

## __init__ {#all}

Initierar en ny instans av Padding‑klassen med den angivna utfyllnadsstorleken för alla kanter.

```python
def __init__(self, all):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| all | `int` | Antalet måttenheter som ska användas för utfyllnad för alla kanter. |

### Exempel

```python
# Enhetlig utfyllnad på 5 enheter på alla sidor
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Initierar en ny instans av Padding‑klassen med de angivna utfyllnadsstorlekarna.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| left | `int` | Vänster utfyllnadsstorlek. |
| right | `int` | Höger utfyllnadsstorlek. |
| top | `int` | Topp utfyllnadsstorlek. |
| bottom | `int` | Den nedre utfyllnadsstorleken. |

### Exempel

```python
from groupdocs.signature.domain import Padding

# Skapa en utfyllnad med högra och nedre förskjutningar
margin = Padding(right=40, bottom=60)
```

### Se även
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
