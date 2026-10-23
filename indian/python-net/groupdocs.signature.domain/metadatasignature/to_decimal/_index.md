---
title: "to_decimal मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "metadata signature मान को Decimal में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

metadata signature मान को Decimal में परिवर्तित करता है।

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद उठाया जाता है। यदि मूल मान स्ट्रिंग-आधारित है, तो [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से डिफ़ॉल्ट संस्कृति प्रॉपर्टी जानकारी का उपयोग किया जाएगा।

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

metadata signature मान को Decimal में परिवर्तित करता है।

```python
def to_decimal(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** The metadata signature value as Decimal.

### संबंधित देखें
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
