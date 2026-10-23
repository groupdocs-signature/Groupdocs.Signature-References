---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "पूर्वनिर्धारित नाम और खाली मान के साथ Spreadsheet Metadata Signature को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

पूर्वनिर्धारित नाम और खाली मान के साथ Spreadsheet Metadata Signature को प्रारंभ करता है।

```python
def __init__(self, name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | Spreadsheet Metadata Signature नाम। |

## __init__ {#name-value}

पूर्वनिर्धारित मानों के साथ Spreadsheet Metadata Signature को प्रारंभ करता है।

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# एक स्प्रेडशीट के लिए मेटाडेटा सिग्नेचर बनाएं
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### संबंधित देखें
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
