---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar standardverifieringsalternativ för streckkodssignatur."
type: docs
url: /sv/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar standardverifieringsalternativ för streckkodssignatur.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Initierar ett standardverifieringsalternativ med verifieringstext.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Streckkodstext att verifiera. |

## __init__ {#encode_type}

Initierar ett standardverifieringsalternativ med streckkodstypverifiering.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| encode_type | `BarcodeType` | Verifiering av streckkodstyp. |

## __init__ {#text-encode_type}

Initierar ett standardverifieringsalternativ med streckkodstypverifiering och text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Streckkodstext att verifiera. |
| encode_type | `BarcodeType` | Verifiering av streckkodstyp. |

### Se även
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
