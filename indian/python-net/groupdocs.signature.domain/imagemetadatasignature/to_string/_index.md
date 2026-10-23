---
title: "to_string मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "मेटाडेटा हस्ताक्षर मान को स्ट्रिंग में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

मेटाडेटा हस्ताक्षर मान को स्ट्रिंग में परिवर्तित करता है।

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

निर्दिष्ट फ़ॉर्मेट का उपयोग करके मेटाडेटा हस्ताक्षर मान को स्ट्रिंग में परिवर्तित करता है।

एक बूलियन प्रॉपर्टी को \"True\" या \"False\" में परिवर्तित करता है। डिफ़ॉल्ट कल्चर जानकारी [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से उपयोग की जाती है।

```python
def to_string(self, format):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| format | `str` | डेटा फ़ॉर्मेट स्ट्रिंग। |

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

**Returns:** str: The metadata signature value as a string.

### संबंधित देखें
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
