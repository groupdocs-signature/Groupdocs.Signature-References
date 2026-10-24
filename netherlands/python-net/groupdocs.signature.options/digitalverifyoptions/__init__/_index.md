---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een DigitalVerifyOptions‑instantie met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een DigitalVerifyOptions‑instantie met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

Initialiseert een DigitalVerifyOptions‑instantie met het opgegeven bestandspad van het digitale certificaat.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_file_path | `str` | Bestandspad naar digitaal certificaat. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Initialiseert een DigitalVerifyOptions‑instantie met de opgegeven certificaat‑stream.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Stroom van het certificaat. |

### Zie ook
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
