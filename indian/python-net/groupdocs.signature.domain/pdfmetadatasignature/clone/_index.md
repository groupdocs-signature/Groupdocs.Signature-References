---
title: "clone मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "Metadata Signature इंस्टेंस को क्लोन करें।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Metadata Signature इंस्टेंस को क्लोन करें।

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### उदाहरण

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # नए मान के साथ मानक मेटाडाटा सिग्नेचर को क्लोन करें
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

दिए गए मान के साथ PDF मेटाडाटा सिग्नेचर इंस्टेंस को क्लोन करता है।

```python
def clone(self, value):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | `Any` | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |

**Returns:** A cloned metadata signature instance.

### उदाहरण

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# मौजूदा मेटाडाटा सिग्नेचर को नई मान के साथ क्लोन करें
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### संबंधित देखें
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
