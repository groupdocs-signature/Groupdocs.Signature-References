---
title: "VerificationResult क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "वेरिफिकेशन प्रक्रिया के परिणामों को रखने वाले इंस्टेंस का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

वेरिफिकेशन प्रक्रिया के परिणामों को रखने वाले इंस्टेंस का प्रतिनिधित्व करता है।

VerificationResult प्रकार निम्नलिखित सदस्य उजागर करता है:

### गुण
| गुण | विवरण |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | गंतव्य दस्तावेज़ आकार। सत्यापन के लिए यह चर हमेशा शून्य रखता है। |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | सत्यापन प्रक्रिया में विफल हुए हस्ताक्षरों की सूची। |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | सत्यापन परिणाम; यदि सत्यापन प्रक्रिया सफल है तो True, अन्यथा False। |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | प्रक्रिया का निष्पादन समय मिलीसेकंड में। |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | स्रोत दस्तावेज़ आकार बाइट्स में। |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | सफलतापूर्वक सत्यापित हस्ताक्षरों की सूची [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | प्रसंस्कृत हस्ताक्षरों की कुल संख्या। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
