---
title: "QrCodeVerifyOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ QR-code सिग्नेचर को सत्यापित करने के विकल्पों को रखता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

दस्तावेज़ QR-code सिग्नेचर को सत्यापित करने के विकल्पों को रखता है।

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

QrCodeVerifyOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | QR-कोड हस्ताक्षरों के लिए सत्यापन विकल्पों को प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | निर्दिष्ट QR-कोड पाठ के साथ QR-कोड हस्ताक्षरों के लिए सत्यापन विकल्पों को प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | पाठ और सत्यापन के लिए QR-कोड एन्कोड प्रकार के साथ QR-कोड हस्ताक्षरों के लिए सत्यापन विकल्पों को प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) का कार्यान्वयन QR-Code हस्ताक्षर टेक्स्ट गुणों को एन्कोड और डिकोड करने के लिए उपयोग किया जाता है। |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | QR-code प्रकार सत्यापन। यह गुण वैकल्पिक है। |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | यह फ़्लैग दर्शाता है कि क्या प्रत्येक दस्तावेज़ पेज की जाँच की जानी चाहिए। डिफ़ॉल्ट रूप से मान True है। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | वैकल्पिक सिग्नेचर विकल्पों की जाँच के लिए अतिरिक्त एक्सटेंशन। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | सत्यापन के लिए फ़ॉर्म फ़ील्ड का शीर्षक। यदि सेट किया गया है, तो टेक्स्ट केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा। (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | सत्यापन के लिए फ़ॉर्म फ़ील्ड का प्रकार; यदि सेट किया गया है, तो टेक्स्ट केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा। (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | वैध प्रॉपर्टी फ़्लैग। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | टेक्स्ट मिलान प्रकार सत्यापन। (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | जाँच के लिए दस्तावेज़ पेज संख्या; यदि सेट नहीं है, तो दस्तावेज़ के सभी पेज पहली घटना के लिए जाँचे जाते हैं (न्यूनतम मान 1 है)। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | जाँच के लिए पेज निर्दिष्ट करने के पेज विकल्प। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | हेडर/फ़ूटर में सिग्नेचर की जाँच के लिए दस्तावेज़ लेआउट में शैप की स्थिति। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | सत्यापन के लिए टेक्स्ट सिग्नेचर ID। शून्य से बड़ा होना चाहिए; केवल PDF दस्तावेज़ों के लिए समर्थित। (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | सत्यापन के लिए सिग्नेचर का प्रकार। (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | सत्यापन के लिए सिग्नेचर टेक्स्ट। (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
