---
title: "FormFieldSearchOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़ॉर्म-फ़ील्ड हस्ताक्षरों के लिए खोज विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

फ़ॉर्म-फ़ील्ड हस्ताक्षरों के लिए खोज विकल्प दर्शाता है।

और अधिक जानें:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

FormFieldSearchOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | डिफ़ॉल्ट मानों के साथ FormFieldSearchOptions क्लास का नया उदाहरण आरंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | खोज के दौरान फ़ॉर्म फ़ील्ड सिग्नेचर नाम से मेल खाने के लिए उपयोग किया जाने वाला नियमित अभिव्यक्ति पैटर्न। |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | खोज के लिए फ़ॉर्म फ़ील्ड सिग्नेचर का प्रकार। डिफ़ॉल्ट मान None है। |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | खोज के लिए फ़ॉर्म फ़ील्ड सिग्नेचर का मान। डिफ़ॉल्ट None है। |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | फ़्लैग जो संकेत करता है कि प्रत्येक दस्तावेज़ पृष्ठ पर खोज करनी है या नहीं। डिफ़ॉल्ट रूप से यह मान True है। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | खोज के लिए दस्तावेज़ पृष्ठ संख्या (वैकल्पिक)। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | फ़्लैग जो संकेत करता है कि दस्तावेज़ लेआउट में आकार की स्थिति लौटानी है या नहीं। केवल Word दस्तावेज़ों के लिए उपलब्ध। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | फ़्लैग जो केवल `IsSignature` के रूप में चिह्नित हस्ताक्षर लौटाता है। डिफ़ॉल्ट रूप से मान `False` है, जो दर्शाता है कि निर्दिष्ट मानदंड से मेल खाने वाले सभी हस्ताक्षर लौटाए जाते हैं। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # केवल उन टेक्स्ट फ़ील्ड को लौटाएँ जिनका नाम \"ApprovedBy\" है
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
