---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the DigitalVBA class with a certificate file."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Initializes a new instance of the DigitalVBA class with a certificate file.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Digital certificate file path. |
| password | `str` | Digital certificate password. |

### Example

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Create a DigitalVBA extension using a certificate file and password
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Initializes a new instance of the DigitalVBA class with a certificate stream.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase containing the digital certificate. |
| password | `str` | str password for the digital certificate. |

### See Also
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
