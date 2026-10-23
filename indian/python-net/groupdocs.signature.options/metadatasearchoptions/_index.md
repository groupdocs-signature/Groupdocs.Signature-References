---
title: "MetadataSearchOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "मेटाडेटा सिग्नेचर के लिए खोज विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

मेटाडेटा सिग्नेचर के लिए खोज विकल्पों का प्रतिनिधित्व करता है।

एक दस्तावेज़ में मेटाडेटा हस्ताक्षरों की खोज को कॉन्फ़िगर करने के विकल्प प्रदान करता है।

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

MetadataSearchOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | डिफ़ॉल्ट मानों के साथ MetadataSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) का कार्यान्वयन इस विकल्प संग्रह के भीतर सभी मेटाडेटा हस्ताक्षरों को डिक्रिप्ट करने के लिए उपयोग किया जाता है। |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | फ़्लैग यह दर्शाता है कि क्या बिल्ट‑इन दस्तावेज़ गुण जैसे दस्तावेज़ सांख्यिकी और जानकारी खोज परिणाम में शामिल हैं। |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | खोजने और मिलान करने के लिए मेटाडेटा हस्ताक्षर नाम। |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | खोज के लिए उपयोग किया जाने वाला मेटाडेटा नाम मिलान प्रकार। यह केवल तब लागू होता है जब `name` प्रॉपर्टी सेट हो। |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | फ़्लैग जो संकेत करता है कि प्रत्येक दस्तावेज़ पृष्ठ पर खोज करनी है या नहीं। डिफ़ॉल्ट रूप से यह मान True है। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | खोज के लिए दस्तावेज़ पृष्ठ संख्या (वैकल्पिक)। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | फ़्लैग जो संकेत करता है कि दस्तावेज़ लेआउट में आकार की स्थिति लौटानी है या नहीं। केवल Word दस्तावेज़ों के लिए उपलब्ध। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | फ़्लैग जो केवल `IsSignature` के रूप में चिह्नित हस्ताक्षर लौटाता है। डिफ़ॉल्ट रूप से मान `False` है, जो दर्शाता है कि निर्दिष्ट मानदंड से मेल खाने वाले सभी हस्ताक्षर लौटाए जाते हैं। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
