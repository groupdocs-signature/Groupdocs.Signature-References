---
title: "allow_expired प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "वह फ़्लैग जो ऐसी प्रमाणपत्र के साथ साइन करने की अनुमति देता है जिसकी वैधता अवधि समाप्त हो गई है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

सर्टिफ़िकेट जिसकी वैधता अवधि समाप्त हो गई है, उसके साथ साइन करने की अनुमति देने वाला फ़्लैग। डिफ़ॉल्ट मान False है; समाप्त सर्टिफ़िकेट के साथ साइन करने पर `GroupDocsSignatureException` उत्पन्न होता है और दस्तावेज़ साइन नहीं होता।

वैलिडेटर रिपोर्ट करते हैं कि समाप्त प्रमाणपत्र के साथ बनाया गया सिग्नेचर अमान्य है। इस प्रॉपर्टी को केवल तब True सेट करें जब आपको ऐसी सिग्नेचर की आवश्यकता हो, उदाहरण के लिए पुराने प्रमाणपत्र के साथ परीक्षण करने के लिए। तब दस्तावेज़ पर साइन किया जाता है, और एक चेतावनी लॉगर में लिखी जाती है जो [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) में सेट है।

प्रमाणपत्र की तुलना UTC में वर्तमान समय से की जाती है, न कि [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) से। यह फ़्लैग उन प्रमाणपत्रों पर लागू होता है जो [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) या [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/) द्वारा प्रदान किए गए हैं, और जब एक स्प्रेडशीट पर साइन किया जाता है, तो पहले [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) एक्सटेंशन के प्रमाणपत्र पर भी। इमेज की डिजिटल सिग्नेचर प्रमाणपत्र का उपयोग नहीं करती और जांची नहीं जाती। वह प्रमाणपत्र जिसकी वैधता अवधि अभी शुरू नहीं हुई है, [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) द्वारा नियंत्रित होता है।

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### संबंधित देखें
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
