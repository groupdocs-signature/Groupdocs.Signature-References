---
title: "QrCodeSearchOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "QR-Code सिग्नेचर के लिए खोज विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

QR-Code सिग्नेचर के लिए खोज विकल्पों का प्रतिनिधित्व करता है।

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

QrCodeSearchOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | डिफ़ॉल्ट मानों के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | एन्कोड प्रकार मान के साथ QRCodeSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | QRCodeSearchOptions क्लास का नया उदाहरण एन्कोड प्रकार और टेक्स्ट मानों के साथ आरंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए उपयोग किया गया [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) का कार्यान्वयन। |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | QR कोड खोजने के लिए एन्कोड प्रकार। |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | खोज के दौरान उपयोग किया जाने वाला QR-Code टेक्स्ट मिलान प्रकार। |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | एक दस्तावेज़ पृष्ठ पर प्रत्येक हस्ताक्षर के लिए QR‑Code छवि सामग्री लौटाई जाती है या नहीं, यह निर्धारित करने वाला फ़्लैग। जब इसे True सेट किया जाता है, तो कच्चा छवि डेटा हस्ताक्षर की `content` प्रॉपर्टी में `return_content_type` द्वारा निर्दिष्ट फ़ॉर्मेट का उपयोग करके रखा जाता है। डिफ़ॉल्ट रूप से निष्क्रिय। |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | `return_content` प्रॉपर्टी सक्षम होने पर QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार। |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | खोज और मिलान के लिए QR-Code हस्ताक्षर टेक्स्ट। |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | फ़्लैग जो संकेत करता है कि प्रत्येक दस्तावेज़ पृष्ठ पर खोज करनी है या नहीं। डिफ़ॉल्ट रूप से यह मान True है। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | खोज के लिए दस्तावेज़ पृष्ठ संख्या (वैकल्पिक)। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | फ़्लैग जो संकेत करता है कि दस्तावेज़ लेआउट में आकार की स्थिति लौटानी है या नहीं। केवल Word दस्तावेज़ों के लिए उपलब्ध। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | फ़्लैग जो केवल `IsSignature` के रूप में चिह्नित हस्ताक्षर लौटाता है। डिफ़ॉल्ट रूप से मान `False` है, जो दर्शाता है कि निर्दिष्ट मानदंड से मेल खाने वाले सभी हस्ताक्षर लौटाए जाते हैं। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
