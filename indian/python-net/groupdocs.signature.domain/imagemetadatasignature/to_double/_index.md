---
title: "to_double मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़्लोट में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

फ़्लोट में परिवर्तित करता है।

यदि metadata मान को परिवर्तित नहीं किया जा सकता है तो एक अपवाद उठाता है। यदि मूल मान स्ट्रिंग‑आधारित है, तो डिफ़ॉल्ट संस्कृति [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से उपयोग की जाती है।

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

metadata signature मान को float में परिवर्तित करता है।

परिवर्तन करने के लिए निर्दिष्ट फ़ॉर्मेट डेटा प्रोवाइडर का उपयोग करता है।

```python
def to_double(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** float: The metadata signature value as a float.

### संबंधित देखें
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
