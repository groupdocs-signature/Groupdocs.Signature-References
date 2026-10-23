---
title: "to_decimal मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डेसिमल में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

डेसिमल में परिवर्तित करता है।

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सकता है तो एक अपवाद उठाया जाता है। यदि मूल मान स्ट्रिंग-आधारित है, तो [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से डिफ़ॉल्ट संस्कृति का उपयोग किया जाता है।

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

मेटाडेटा हस्ताक्षर मान को दशमलव में परिवर्तित करता है।

यदि मेटाडाटा वैल्यू को परिवर्तित नहीं किया जा सकता तो एक्सेप्शन उठाता है।

```python
def to_decimal(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** float: The metadata signature value as a decimal.

### संबंधित देखें
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
