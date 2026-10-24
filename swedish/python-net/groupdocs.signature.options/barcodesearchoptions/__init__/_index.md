---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av BarcodeSearchOptions-klassen med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av BarcodeSearchOptions-klassen med standardvärden.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Skapa ett sökalternativobjekt med standardinställningar
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Initierar en ny instans av BarcodeSearchOptions-klassen med kodningstypvärde.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| encode_type | `BarcodeType` | Anger streckkodens kodningstyp. |

## __init__ {#encode_type-text}

Initierar en ny instans av BarcodeSearchOptions-klassen med kodningstyp- och textvärden.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| encode_type | `BarcodeType` | Anger streckkodens kodningstyp. |
| text | `str` | Ange text för streckkodssignatur. |

### Se även
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
