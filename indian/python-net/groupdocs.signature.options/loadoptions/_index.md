---
title: "LoadOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "LoadOptions क्लास दस्तावेज़ को साइन करने के लिए खोलते समय अतिरिक्त विकल्प (जैसे पासवर्ड) निर्दिष्ट करने की अनुमति देती है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

LoadOptions क्लास दस्तावेज़ को साइन करने के लिए खोलते समय अतिरिक्त विकल्प (जैसे पासवर्ड) निर्दिष्ट करने की अनुमति देती है।

यदि फ़ाइल एन्क्रिप्टेड है तो `password` एट्रिब्यूट को दस्तावेज़ पासवर्ड पर सेट करें।

LoadOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | LoadOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | निर्दिष्ट फ़ाइल प्रकार के साथ [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) क्लास का नया इंस्टेंस प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | लोड विकल्पों से जुड़ा फ़ाइल प्रकार, डिफ़ॉल्ट रूप से [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/) पर सेट। |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | फ़्लैग जो निर्धारित करता है कि दस्तावेज़ बाहरी संसाधन लोड करता है या नहीं। यह प्रॉपर्टी पुरानी है; इसके बजाय [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) का उपयोग करें, जिसका अर्थ विपरीत है। |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | संरक्षित दस्तावेज़ खोलने और हस्ताक्षरित दस्तावेज़ को संरक्षित रूप में सहेजने के लिए उपयोग किया गया पासवर्ड। |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | PDF दस्तावेज़ अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण। केवल PDF दस्तावेज़ों के लिए। |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | दस्तावेज़ को बाहरी संसाधनों को लोड करने से रोकने वाला फ़्लैग। डिफ़ॉल्ट मान True है; बाहरी संसाधनों को तब तक लोड नहीं किया जाता जब तक वे [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) से मेल नहीं खाते। |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | बाहरी संसाधनों को लोड करने के पते के टुकड़ों की सूची, यहाँ तक कि जब [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true हो। डिफ़ॉल्ट मान एक खाली सूची है। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
