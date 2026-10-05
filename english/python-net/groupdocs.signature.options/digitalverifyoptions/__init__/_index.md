---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a DigitalVerifyOptions instance with default values."
type: docs
url: /python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a DigitalVerifyOptions instance with default values.

```python
def __init__(self):
    ...
```

### Example

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

Initializes a DigitalVerifyOptions instance with the given digital certificate file path.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | File path to digital certificate. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Initializes a DigitalVerifyOptions instance with the given certificate stream.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Certificate's stream. |

### See Also
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
