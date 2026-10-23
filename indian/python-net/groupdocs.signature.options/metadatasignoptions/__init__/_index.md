---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "MetadataSignOptions क्लास का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

MetadataSignOptions क्लास का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    options.signatures.add(
        WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
    )
    result = signature.sign("signed.docx", options)
```

## __init__ {#signatures}

[`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) का एक नया उदाहरण मेटाडेटा के साथ प्रारंभ करता है।

```python
def __init__(self, signatures):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | मेटाडेटा हस्ताक्षरों का संग्रह `MetadataSignature`। |

### उदाहरण

```python
from datetime import datetime
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

signatures = [
    WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes"),
    WordProcessingMetadataSignature("DateCreated", datetime.now()),
]

options = MetadataSignOptions(signatures=signatures)
```

### संबंधित देखें
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
