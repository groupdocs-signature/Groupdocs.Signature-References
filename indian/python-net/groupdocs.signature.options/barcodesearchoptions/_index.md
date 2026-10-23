---
title: "BarcodeSearchOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "बारकोड हस्ताक्षरों के लिए खोज विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

बारकोड हस्ताक्षरों के लिए खोज विकल्प दर्शाता है।

और अधिक जानें:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

BarcodeSearchOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | डिफ़ॉल्ट मानों के साथ BarcodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | एन्कोड प्रकार मान के साथ BarcodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | एन्कोड प्रकार और टेक्स्ट मानों के साथ BarcodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | बारकोड खोज को फ़िल्टर करने के लिए उपयोग किया गया एन्कोड प्रकार; यदि सेट नहीं किया गया, तो खोज सभी समर्थित बारकोड प्रकारों को शामिल करती है। |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | खोज के लिए उपयोग किया गया बारकोड टेक्स्ट मिलान प्रकार। यह केवल तब उपयोग होता है जब `text` प्रॉपर्टी सेट की गई हो। |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | फ़्लैग जो दर्शाता है कि दस्तावेज़ पृष्ठ पर हस्ताक्षर की बारकोड इमेज सामग्री प्राप्त करनी है या नहीं। |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | `return_content` प्रॉपर्टी सक्षम होने पर बारकोड हस्ताक्षर के लिए लौटाई गई इमेज सामग्री का फ़ाइल प्रकार। |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | खोजने और मिलाने के लिए बारकोड हस्ताक्षर का टेक्स्ट। |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | फ़्लैग जो संकेत करता है कि प्रत्येक दस्तावेज़ पृष्ठ पर खोज करनी है या नहीं। डिफ़ॉल्ट रूप से यह मान True है। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | खोज के लिए दस्तावेज़ पृष्ठ संख्या (वैकल्पिक)। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | फ़्लैग जो संकेत करता है कि दस्तावेज़ लेआउट में आकार की स्थिति लौटानी है या नहीं। केवल Word दस्तावेज़ों के लिए उपलब्ध। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | फ़्लैग जो केवल `IsSignature` के रूप में चिह्नित हस्ताक्षर लौटाता है। डिफ़ॉल्ट रूप से मान `False` है, जो दर्शाता है कि निर्दिष्ट मानदंड से मेल खाने वाले सभी हस्ताक्षर लौटाए जाते हैं। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
`BarcodeSearchOptions` का उपयोग करने वाले टास्क गाइड्स:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
