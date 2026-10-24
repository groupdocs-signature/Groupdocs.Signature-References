---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert de standaard verificatieoptie voor barcodesignatuur."
type: docs
url: /nl/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert de standaard verificatieoptie voor barcodesignatuur.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Initialiseert een standaard verificatieoptie met verificatietekst.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Barcode-tekst om te verifiëren. |

## __init__ {#encode_type}

Initialiseert een standaard verificatieoptie met verificatie van barcodetype.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barcode-type verificatie. |

## __init__ {#text-encode_type}

Initialiseert een standaard verificatieoptie met barcode-type verificatie en tekst.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Barcode-tekst om te verifiëren. |
| encode_type | `BarcodeType` | Barcode-type verificatie. |

### Zie ook
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
