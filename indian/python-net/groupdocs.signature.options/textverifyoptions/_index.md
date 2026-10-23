---
title: "TextVerifyOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ टेक्स्ट हस्ताक्षर को सत्यापित करने के विकल्प रखता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

दस्तावेज़ टेक्स्ट हस्ताक्षर को सत्यापित करने के विकल्प रखता है।

और अधिक जानें:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

TextVerifyOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | TextVerifyOptions का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | TextVerifyOptions का एक नया उदाहरण सत्यापन पाठ के साथ आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | सत्यापित करने के पाठ और हस्ताक्षर कार्यान्वयन प्रकार के साथ एक नया TextVerifyOptions उदाहरण आरंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | सत्यापित करने के फ़ॉर्म फ़ील्ड का शीर्षक। यदि सेट किया गया है, तो पाठ केवल टेक्स्ट फ़ॉर्म फ़ील्ड में मिलेगा। |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | सत्यापन के लिए फ़ॉर्म फ़ील्ड का प्रकार; यदि सेट किया गया है, तो टेक्स्ट केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा। |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | टेक्स्ट मिलान प्रकार सत्यापन। |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | सत्यापन के लिए टेक्स्ट सिग्नेचर आईडी। शून्य से बड़ा होना चाहिए; केवल PDF दस्तावेज़ों के लिए समर्थित। |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | सत्यापित किए जाने वाले सिग्नेचर का प्रकार। |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | सत्यापन के लिए सिग्नेचर टेक्स्ट। |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | यह फ़्लैग दर्शाता है कि क्या प्रत्येक दस्तावेज़ पेज की जाँच की जानी चाहिए। डिफ़ॉल्ट रूप से मान True है। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | वैकल्पिक सिग्नेचर विकल्पों की जाँच के लिए अतिरिक्त एक्सटेंशन। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | वैध प्रॉपर्टी फ़्लैग। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | जाँच के लिए दस्तावेज़ पेज संख्या; यदि सेट नहीं है, तो दस्तावेज़ के सभी पेज पहली घटना के लिए जाँचे जाते हैं (न्यूनतम मान 1 है)। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | जाँच के लिए पेज निर्दिष्ट करने के पेज विकल्प। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | हेडर/फ़ूटर में सिग्नेचर की जाँच के लिए दस्तावेज़ लेआउट में शैप की स्थिति। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
`TextVerifyOptions` का उपयोग करने वाले टास्क गाइड्स:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
