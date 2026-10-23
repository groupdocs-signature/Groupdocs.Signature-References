---
title: "include_standard_metadata_signatures प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़्लैग जो यह दर्शाता है कि मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे Author, Owner, निर्माण तिथि, और संशोधित तिथि मेटाडेटा सूची में शामिल हैं या नहीं।"
type: docs
url: /hi/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

फ़्लैग जो यह दर्शाता है कि मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे Author, Owner, निर्माण तिथि, और संशोधित तिथि मेटाडेटा सूची में शामिल हैं या नहीं।

यदि इसे False (डिफ़ॉल्ट) पर सेट किया जाता है, तो GetDocumentInfo इन मेटाडेटा हस्ताक्षरों को शामिल नहीं करेगा। जब इसे True पर सेट किया जाता है, तो दस्तावेज़ जानकारी में मानक मेटाडेटा हस्ताक्षर शामिल होंगे।

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### संबंधित देखें
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
