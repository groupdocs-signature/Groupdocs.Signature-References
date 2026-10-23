---
title: "to_date_time मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "मेटाडाटा सिग्नेचर वैल्यू को datetime.datetime में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

मेटाडेटा हस्ताक्षर मान को `datetime.datetime` में परिवर्तित करता है।

यदि metadata मान को परिवर्तित नहीं किया जा सकता है तो एक अपवाद उठाता है। यदि मूल मान स्ट्रिंग‑आधारित है, तो डिफ़ॉल्ट संस्कृति [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से उपयोग की जाती है।

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

मेटाडेटा हस्ताक्षर मान को `datetime` में परिवर्तित करता है।

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है।

```python
def to_date_time(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** datetime: The metadata signature value as a `datetime`.

### संबंधित देखें
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
