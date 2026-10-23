---
title: "to_double मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "metadata signature मान को float में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

metadata signature मान को float में परिवर्तित करता है।

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सकता है तो एक अपवाद उठाया जाता है। यदि मूल मान स्ट्रिंग-आधारित है, तो [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से डिफ़ॉल्ट संस्कृति का उपयोग किया जाता है।

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Double में परिवर्तित करता है।

```python
def to_double(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** float: The metadata signature value as a float.

### संबंधित देखें
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
