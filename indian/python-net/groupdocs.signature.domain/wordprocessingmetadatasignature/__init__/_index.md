---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "निर्दिष्ट नाम और खाली मान के साथ एक WordProcessingMetadataSignature को आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

निर्दिष्ट नाम और खाली मान के साथ एक WordProcessingMetadataSignature को आरंभ करता है।

```python
def __init__(self, name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature नाम। |

### उदाहरण

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# नाम और मान के साथ मेटाडाटा सिग्नेचर बनाएं
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

पूर्वनिर्धारित मानों के साथ एक WordProcessing मेटाडेटा हस्ताक्षर को आरंभ करता है।

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### संबंधित देखें
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
