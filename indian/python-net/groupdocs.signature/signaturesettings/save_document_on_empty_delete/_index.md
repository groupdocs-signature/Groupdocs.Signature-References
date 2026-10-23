---
title: "save_document_on_empty_delete प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़्लैग जो निर्धारित करता है कि जब Delete मेथड के पास हटाने के लिए कोई प्रभावित हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः‑सहेजा जाए या नहीं।"
type: docs
url: /hi/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

फ़्लैग जो निर्धारित करता है कि जब Delete मेथड के पास हटाने के लिए कोई प्रभावित हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः‑सहेजा जाए या नहीं।

जब True (डिफ़ॉल्ट) हो, तो दस्तावेज़ को इतिहास लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाता है भले ही कोई हस्ताक्षर हटाया न गया हो; जब False हो, तो स्रोत दस्तावेज़ अपरिवर्तित रहता है।

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### संबंधित देखें
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
