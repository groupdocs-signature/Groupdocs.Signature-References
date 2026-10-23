---
title: "to_single मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "metadata signature मान को float में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

metadata signature मान को float में परिवर्तित करता है।

यदि metadata मान को परिवर्तित नहीं किया जा सकता है तो एक अपवाद उठाता है। यदि मूल मान स्ट्रिंग‑आधारित है, तो डिफ़ॉल्ट संस्कृति [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से उपयोग की जाती है।

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

float में परिवर्तित करता है।

```python
def to_single(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** float: The Metadata Signature value as float.

### संबंधित देखें
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
