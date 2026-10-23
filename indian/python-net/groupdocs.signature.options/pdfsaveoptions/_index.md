---
title: "PdfSaveOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "PDF दस्तावेज़ों के लिए सहेजने विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

PDF दस्तावेज़ों के लिए सहेजने विकल्पों का प्रतिनिधित्व करता है।

PdfSaveOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | डिफ़ॉल्ट मानों के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | निर्दिष्ट आउटपुट फ़ाइल स्वरूप के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | ओवरराइट फ़्लैग के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | निर्दिष्ट आउटपुट फ़ाइल स्वरूप और ओवरराइट फ़्लैग के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | हस्ताक्षरित दस्तावेज़ का फ़ाइल फ़ॉर्मेट। |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण। |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | अनुमति सेटिंग्स बदलने के लिए आवश्यक अनुमति पासवर्ड (मुख्य पासवर्ड)। |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | यह फ़्लैग निर्धारित करता है कि आउटपुट फ़ाइल पाथ में यदि एक्सटेंशन गायब हो तो उसे स्वचालित रूप से जोड़ना है या नहीं। डिफ़ॉल्ट मान False है। ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) से विरासत में मिला) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | यह फ़्लैग दर्शाता है कि नई आउटपुट फ़ाइल से मौजूदा फ़ाइल को ओवरराइट करना है या नहीं। ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) से विरासत में मिला) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | सहेजे गए साइन किए गए दस्तावेज़ की सुरक्षा के लिए उपयोग किया गया पासवर्ड। इमेज दस्तावेज़ों के लिए समर्थित नहीं है। ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) से विरासत में मिला) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | साइन किए गए दस्तावेज़ को संरक्षित रूप में सहेजते समय [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) से पासवर्ड उपयोग करने का फ़्लैग। डिफ़ॉल्ट मान True है। इमेज दस्तावेज़ों के लिए समर्थित नहीं है। ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) से विरासत में मिला) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
