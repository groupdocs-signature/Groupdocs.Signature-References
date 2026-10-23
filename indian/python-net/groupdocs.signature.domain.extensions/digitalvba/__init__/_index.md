---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिजिटलVBA क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल के साथ इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

डिजिटलVBA क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल के साथ इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_file_path, password):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_file_path | `str` | डिजिटल प्रमाणपत्र फ़ाइल पथ। |
| password | `str` | डिजिटल प्रमाणपत्र पासवर्ड। |

### उदाहरण

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# एक प्रमाणपत्र फ़ाइल और पासवर्ड का उपयोग करके DigitalVBA एक्सटेंशन बनाएं
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

डिजिटलVBA क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम के साथ इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_stream, password):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | डिजिटल प्रमाणपत्र को शामिल करने वाला io.RawIOBase। |
| password | `str` | डिजिटल प्रमाणपत्र के लिए str पासवर्ड। |

### संबंधित देखें
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
