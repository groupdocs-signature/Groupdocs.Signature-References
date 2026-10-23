---
title: "clone मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "FormField Signature इंस्टेंस को क्लोन करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField Signature इंस्टेंस को क्लोन करता है।

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### उदाहरण

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# नए मान के साथ एक मेटाडाटा हस्ताक्षर को क्लोन करें
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### संबंधित देखें
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
