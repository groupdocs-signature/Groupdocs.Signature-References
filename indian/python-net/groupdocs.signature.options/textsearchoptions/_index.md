---
title: "TextSearchOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "टेक्स्ट हस्ताक्षर के लिए खोज विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

टेक्स्ट हस्ताक्षर के लिए खोज विकल्पों का प्रतिनिधित्व करता है।

और अधिक जानें:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

TextSearchOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | डिफ़ॉल्ट मानों के साथ TextSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | टेक्स्ट मान के साथ TextSearchOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | खोज के लिए उपयोग किया गया टेक्स्ट मिलान प्रकार। |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | खोज के लिए टेक्स्ट सिग्नेचर इम्प्लीमेंटेशन। |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | खोज के समय मिलाने के लिए सिग्नेचर टेक्स्ट। |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | फ़्लैग जो संकेत करता है कि प्रत्येक दस्तावेज़ पृष्ठ पर खोज करनी है या नहीं। डिफ़ॉल्ट रूप से यह मान True है। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | खोज के लिए दस्तावेज़ पृष्ठ संख्या (वैकल्पिक)। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | फ़्लैग जो संकेत करता है कि दस्तावेज़ लेआउट में आकार की स्थिति लौटानी है या नहीं। केवल Word दस्तावेज़ों के लिए उपलब्ध। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | फ़्लैग जो केवल `IsSignature` के रूप में चिह्नित हस्ताक्षर लौटाता है। डिफ़ॉल्ट रूप से मान `False` है, जो दर्शाता है कि निर्दिष्ट मानदंड से मेल खाने वाले सभी हस्ताक्षर लौटाए जाते हैं। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
`TextSearchOptions` का उपयोग करने वाले टास्क गाइड्स:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
