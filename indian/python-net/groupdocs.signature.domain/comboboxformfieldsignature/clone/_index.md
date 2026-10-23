---
title: "clone मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "FormField हस्ताक्षर उदाहरण को क्लोन करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField हस्ताक्षर उदाहरण को क्लोन करता है।

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### उदाहरण

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# एक मूल कॉम्बॉबॉक्स फ़ॉर्म फ़ील्ड सिग्नेचर बनाएं
original = ComboboxFormFieldSignature()

# सिग्नेचर को क्लोन करें
cloned = original.clone()
```

### संबंधित देखें
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
