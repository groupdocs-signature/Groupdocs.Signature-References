---
title: "try_parse विधि"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दिए गए पार्सिंग प्रकार नाम से मेल खाने वाला Barcode प्रकार लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

दिए गए पार्सिंग प्रकार नाम से मेल खाने वाला Barcode प्रकार लौटाता है।

यदि नाम अज्ञात है, तो विधि अपवाद उठाए बिना None लौटाती है।

```python
def try_parse(cls, parsing_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| parsing_type | `str` | बारकोड प्रकार नाम की स्रोत स्ट्रिंग। |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### संबंधित देखें
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
