---
title: "load_external_resources प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़्लैग जो निर्धारित करता है कि दस्तावेज़ बाहरी संसाधन लोड करता है या नहीं।"
type: docs
url: /hi/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

फ़्लैग जो निर्धारित करता है कि दस्तावेज़ बाहरी संसाधन लोड करता है या नहीं। यह प्रॉपर्टी पुरानी है; इसके बजाय [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) का उपयोग करें, जिसका अर्थ विपरीत है।

LoadExternalResources = True, `SkipExternalResources` = False के बराबर है, और LoadExternalResources = False, `SkipExternalResources` = True के बराबर है। डिफ़ॉल्ट मान False है, जिसका अर्थ है कि बाहरी संसाधन तब तक लोड नहीं होते जब तक स्पष्ट रूप से अनुमति न दी जाए।

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### संबंधित देखें
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
