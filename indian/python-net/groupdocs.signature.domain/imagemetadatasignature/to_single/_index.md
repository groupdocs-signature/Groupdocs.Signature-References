---
title: "to_single मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "float में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

float में परिवर्तित करता है।

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सकता तो एक अपवाद फेंका जाता है। यदि मूल मान स्ट्रिंग आधारित है, तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से उपयोग की जाएगी।

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

metadata signature मान को float में परिवर्तित करता है।

यदि मेटाडाटा वैल्यू को परिवर्तित नहीं किया जा सकता तो एक्सेप्शन उठाता है।

```python
def to_single(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** float: The metadata signature value as a float.

### संबंधित देखें
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
