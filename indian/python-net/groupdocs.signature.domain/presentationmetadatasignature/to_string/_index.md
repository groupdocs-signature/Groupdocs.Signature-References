---
title: "to_string मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "metadata signature को स्ट्रिंग में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/presentationmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

metadata signature को स्ट्रिंग में परिवर्तित करता है।

एक बूलियन प्रॉपर्टी को \"True\" या \"False\" में परिवर्तित करता है। अन्य डेटा प्रकारों के लिए डिफ़ॉल्ट डेटा फ़ॉर्मेट प्रोवाइडर का उपयोग किया जाता है।

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है।

एक बूलियन प्रॉपर्टी को "True" या "False" में परिवर्तित करता है।

```python
def to_string(self, format, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| format | `str` | डेटा फ़ॉर्मेट स्ट्रिंग। |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** str: The metadata signature value as string.

### संबंधित देखें
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
