---
title: "skip_external_resources प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़्लैग जो दस्तावेज़ को बाहरी संसाधन लोड करने से रोकता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

दस्तावेज़ को बाहरी संसाधनों को लोड करने से रोकने वाला फ़्लैग। डिफ़ॉल्ट मान True है; बाहरी संसाधनों को तब तक लोड नहीं किया जाता जब तक वे [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) से मेल नहीं खाते।

एक दस्तावेज़ बाहरी रूप से संग्रहीत संसाधनों को संदर्भित कर सकता है, जैसे लिंक्ड इमेजेज, INCLUDEPICTURE फ़ील्ड द्वारा डाली गई तस्वीरें, प्रस्तुतियों और स्प्रेडशीट्स में लिंक्ड तस्वीरें, तथा SVG इमेज द्वारा संदर्भित इमेजेज और स्टाइल शीट्स। ऐसे संसाधन को लोड करने से लाइब्रेरी उसका पता अनुरोध करती है। अनविश्वसनीय दस्तावेज़ों को प्रोसेस करने वाले सर्वर पर, एक दस्तावेज़ इसका उपयोग करके सर्वर को आंतरिक पतों पर अनुरोध भेजा सकता है (सर्वर‑साइड अनुरोध जाल), और एक UNC या `file://` पाथ विंडोज को खाते की NTLM क्रेडेंशियल्स दूसरे होस्ट को भेजने का कारण बन सकता है। ऑफ़लाइन या एयर‑गैप्ड इंस्टॉलेशन पर, अनुरोध विफल हो जाते हैं या टाइम‑आउट तक प्रतीक्षा करते हैं।

छोड़े गए संसाधनों को पेज प्रीव्यू में या इमेज के रूप में सहेजे गए दस्तावेज़ों में नहीं दिखाया जाता, और इमेज, बारकोड, तथा QR‑कोड खोज उन्हें नहीं देखती। इस प्रॉपर्टी को केवल विश्वसनीय दस्तावेज़ों के लिए False सेट करें, और विशिष्ट पतों को अनुमति देने के लिए [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) का उपयोग करना बेहतर है।

यह सेटिंग वर्ड प्रोसेसिंग दस्तावेज़ों, प्रस्तुतियों, स्प्रेडशीट्स और SVG इमेजेज पर लागू होती है, जिसमें आर्काइव के अंदर के दस्तावेज़ भी शामिल हैं। SVG इमेजेज के लिए, अनधिकृत रेफ़रेंसेज़ को पढ़ने से पहले इमेज से हटा दिया जाता है, और जो SVG इमेज ठीक‑से‑फ़ॉर्मेटेड XML नहीं है, उसे अस्वीकार कर दिया जाता है। यह सेटिंग प्रमाणपत्र रद्दीकरण जांच, टाइम‑स्टैम्प सर्वर, या लाइसेंसिंग को नियंत्रित नहीं करती।

यह प्रॉपर्टी [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) को बदलती है, जिसका अर्थ विपरीत है।

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### संबंधित देखें
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
