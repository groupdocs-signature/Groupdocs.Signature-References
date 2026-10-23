---
title: "whitelisted_resources प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "बाहरी संसाधनों के पते के फ्रैगमेंट की सूची जो LoadOptions.SkipExternalResources true होने पर भी लोड होते हैं।"
type: docs
url: /hi/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

बाहरी संसाधनों को लोड करने के पते के टुकड़ों की सूची, यहाँ तक कि जब [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true हो। डिफ़ॉल्ट मान एक खाली सूची है।

जब किसी संसाधन का पूरा पता इन फ्रैगमेंट्स में से किसी एक को शामिल करता है, तो वह लोड होता है। तुलना केस को अनदेखा करती है, और खाली फ्रैगमेंट्स को नजरअंदाज किया जाता है। `\"https://cdn.example.com/images/\"` जैसे लंबे फ्रैगमेंट को प्राथमिकता दें: एक छोटा फ्रैगमेंट भी उन अन्य पतों से मेल खा सकता है जिनमें वह मौजूद है।

इस प्रॉपर्टी को `None` सेट करने से सूची साफ़ हो जाती है। जब [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) false होता है, तो सूची का कोई प्रभाव नहीं रहता, क्योंकि तब सभी बाहरी संसाधन लोड होते हैं।

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### संबंधित देखें
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
