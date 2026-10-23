---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "पूर्वनिर्धारित नाम और खाली मान के साथ PDF मेटाडाटा सिग्नेचर को आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

पूर्वनिर्धारित नाम और खाली मान के साथ PDF मेटाडाटा सिग्नेचर को आरंभ करता है।

```python
def __init__(self, name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | PDF मेटाडाटा सिग्नेचर का नाम। |

## __init__ {#name-value}

पूर्वनिर्धारित मानों के साथ PDF मेटाडाटा सिग्नेचर को आरंभ करता है।

```python
def __init__(self, name, value):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | मेटाडाटा सिग्नेचर ऑब्जेक्ट का नाम। |
| value | `Any` | मेटाडाटा सिग्नेचर का मान। |

### उदाहरण

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

पूर्वनिर्धारित मानों के साथ PDF मेटाडाटा सिग्नेचर को आरंभ करता है।

```python
def __init__(self, name, value, tag):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | मेटाडाटा सिग्नेचर ऑब्जेक्ट का नाम। |
| value | `Any` | मेटाडाटा सिग्नेचर का मान। |
| tag | `str` | मेटाडाटा सिग्नेचर का प्रीफ़िक्स टैग। |

### उदाहरण

```python
from groupdocs.signature.domain import PdfMetadataSignature

# PDF लेखक के लिए मेटाडाटा सिग्नेचर बनाएं
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# निर्माण तिथि के लिए मेटाडाटा सिग्नेचर बनाएं
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# संख्यात्मक पहचानकर्ता के लिए मेटाडाटा सिग्नेचर बनाएं
id_sig = PdfMetadataSignature("DocumentId", 123456)

# फ़्लोटिंग‑पॉइंट मान के लिए मेटाडाटा सिग्नेचर बनाएं
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### संबंधित देखें
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
