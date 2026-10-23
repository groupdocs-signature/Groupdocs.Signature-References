---
title: "color_resolution प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "GIF रंग रिज़ॉल्यूशन।"
type: docs
url: /hi/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

GIF रंग रिज़ॉल्यूशन।

Color Resolution - मूल इमेज में प्रत्येक प्राथमिक रंग के लिए उपलब्ध बिट्स की संख्या, माइनस 1। यह मान ग्राफिक में चुने गए रंगों के पूरे पैलेट का आकार दर्शाता है, न कि ग्राफिक में वास्तविक उपयोग किए गए रंगों की संख्या। उदाहरण के लिए, यदि इस फ़ील्ड में मान 3 है, तो मूल इमेज के पैलेट में प्रत्येक प्राथमिक रंग के लिए 4 बिट्स उपलब्ध थे जिससे इमेज बनाई गई। इस मान को मूल पैलेट की समृद्धि दर्शाने के लिए सेट किया जाना चाहिए, भले ही स्रोत मशीन पर पूरे पैलेट के सभी रंग उपलब्ध न हों।

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### संबंधित देखें
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
