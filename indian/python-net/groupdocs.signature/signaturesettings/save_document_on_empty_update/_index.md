---
title: "save_document_on_empty_update प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़्लैग जो निर्धारित करता है कि जब Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर न हो तो स्रोत दस्तावेज़ को पुनः‑सहेजा जाए या नहीं।"
type: docs
url: /hi/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

फ़्लैग जो निर्धारित करता है कि जब `Update` मेथड के पास अपडेट करने के लिए कोई हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः‑सहेजा जाए या नहीं।

यदि इसे `True` (डिफ़ॉल्ट) पर सेट किया जाता है, तो दस्तावेज़ को संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाता है भले ही कोई हस्ताक्षर अपडेट न किया गया हो। जब इसे `False` पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल भी संशोधित नहीं होता।

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### संबंधित देखें
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
