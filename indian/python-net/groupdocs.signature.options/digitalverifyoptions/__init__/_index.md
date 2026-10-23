---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ DigitalVerifyOptions का एक इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ DigitalVerifyOptions का एक इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

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

दिए गए डिजिटल प्रमाणपत्र फ़ाइल पथ के साथ DigitalVerifyOptions का एक इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_file_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_file_path | `str` | डिजिटल प्रमाणपत्र का फ़ाइल पथ। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

दिए गए प्रमाणपत्र स्ट्रीम के साथ DigitalVerifyOptions का एक इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | प्रमाणपत्र की स्ट्रीम। |

### संबंधित देखें
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
