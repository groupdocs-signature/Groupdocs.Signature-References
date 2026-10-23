---
title: "clone मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "Metadata Signature इंस्टेंस को क्लोन करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Metadata Signature इंस्टेंस को क्लोन करता है।

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### उदाहरण

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# पूर्वनिर्धारित AUTHOR हस्ताक्षर के आधार पर एक नया metadata हस्ताक्षर बनाएं
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

दिए गए मान के साथ Metadata Signature इंस्टेंस को क्लोन करें।

```python
def clone(self, value):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | `Any` | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### उदाहरण

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# मौजूदा मेटाडाटा सिग्नेचर को नई मान के साथ क्लोन करें
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### संबंधित देखें
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
