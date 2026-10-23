---
title: "BarcodeVerifyOptions वर्ग"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "बारकोड सत्यापन विकल्पों को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---


## BarcodeVerifyOptions class

बारकोड सत्यापन विकल्पों को दर्शाता है।

और अधिक जानें
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings

BarcodeVerifyOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/) | बारकोड हस्ताक्षर के लिए डिफ़ॉल्ट सत्यापन विकल्प आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text) | सत्यापन पाठ के साथ डिफ़ॉल्ट सत्यापन विकल्प आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#encode_type) | बारकोड प्रकार सत्यापन के साथ डिफ़ॉल्ट सत्यापन विकल्प आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text-encode_type) | डिफ़ॉल्ट सत्यापन विकल्प को बारकोड प्रकार सत्यापन और टेक्स्ट के साथ प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type/) | सत्यापन के लिए उपयोग किया गया बारकोड प्रकार। |
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
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import BarcodeVerifyOptions


def verify_barcode_signatures():
    with Signature("signed.pdf") as signature:
        options = BarcodeVerifyOptions()
        options.all_pages = True
        options.text = "12345"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document was verified successfully: {len(result.succeeded)} matching barcode signature(s).")
        else:
            print("Document failed verification process.")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
