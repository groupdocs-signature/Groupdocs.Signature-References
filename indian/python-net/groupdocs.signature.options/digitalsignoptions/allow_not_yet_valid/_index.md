---
title: "allow_not_yet_valid प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "वह फ़्लैग जो ऐसे प्रमाणपत्र के साथ साइन करने की अनुमति देता है जिसकी वैधता अवधि अभी शुरू नहीं हुई है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

सर्टिफ़िकेट जिसकी वैधता अवधि अभी शुरू नहीं हुई है, उसके साथ साइन करने की अनुमति देने वाला फ़्लैग। डिफ़ॉल्ट मान False है; ऐसे सर्टिफ़िकेट के साथ साइन करने पर `GroupDocsSignatureException` उत्पन्न होता है और दस्तावेज़ साइन नहीं होता।

वैलिडेटर रिपोर्ट करते हैं कि प्रमाणपत्र के वैध होने से पहले बनाया गया सिग्नेचर अमान्य है। ऐसा प्रमाणपत्र आमतौर पर बाद की तिथि के लिए जारी किया जाता है, या कंप्यूटर की घड़ी गलत होती है। जब यह फ़्लैग True होता है, तो दस्तावेज़ पर साइन किया जाता है, और एक चेतावनी लॉगर में लिखी जाती है जो [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) में सेट है।

प्रमाणपत्र की तुलना UTC में वर्तमान समय से की जाती है। यह फ़्लैग उसी प्रमाणपत्रों पर लागू होता है जैसा कि [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) में है, जो उन प्रमाणपत्रों को नियंत्रित करता है जिनकी वैधता अवधि समाप्त हो गई है।

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### संबंधित देखें
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
