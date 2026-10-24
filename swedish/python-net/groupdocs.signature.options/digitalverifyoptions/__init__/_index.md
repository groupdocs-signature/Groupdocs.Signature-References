---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en DigitalVerifyOptions‑instans med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en DigitalVerifyOptions‑instans med standardvärden.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

Initierar en DigitalVerifyOptions‑instans med den angivna sökvägen till det digitala certifikatet.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_file_path | `str` | Filsökväg till digitalt certifikat. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Initierar en DigitalVerifyOptions‑instans med den angivna certifikatströmmen.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Certifikatets ström. |

### Se även
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
