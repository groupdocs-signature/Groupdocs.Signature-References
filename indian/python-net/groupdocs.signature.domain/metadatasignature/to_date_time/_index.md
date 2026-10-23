---
title: "to_date_time मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "metadata signature मान को datetime में परिवर्तित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

metadata signature मान को datetime में परिवर्तित करता है।

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सकता है, तो एक अपवाद उठाया जाता है। जब मूल मान स्ट्रिंग‑आधारित होता है, तो रूपांतरण के लिए [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) से डिफ़ॉल्ट संस्कृति का उपयोग किया जाता है।

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

metadata signature मान को datetime में परिवर्तित करता है।

```python
def to_date_time(self, provider):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| provider | `System.IFormatProvider` | डेटा रूपांतरण संचालन के साथ उपयोग के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है।

### संबंधित देखें
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
