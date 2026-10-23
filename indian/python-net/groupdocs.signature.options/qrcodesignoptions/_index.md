---
title: "QrCodeSignOptions वर्ग"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "QR-Code सिग्नेचर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

QR-Code सिग्नेचर विकल्पों का प्रतिनिधित्व करता है।

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

QrCodeSignOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | डिफ़ॉल्ट मानों के साथ QRCodeSignOptions वर्ग का एक नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | निर्दिष्ट टेक्स्ट के साथ QR कोड सिग्नेचर विकल्पों का एक इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | टेक्स्ट के साथ QrCodeSignOptions वर्ग का एक नया इंस्टेंस प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | परिणामी QR-कोड छवि में टेक्स्ट का संरेखण, डिफ़ॉल्ट मान None है। |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | QR-कोड सामग्री में सीरियलाइज़ करने के लिए कस्टम ऑब्जेक्ट। |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | QR कोड सिग्नेचर टेक्स्ट या डेटा को एन्कोड और डिकोड करने के लिए उपयोग किया गया डेटा एन्क्रिप्शन इम्प्लीमेंटेशन। |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | QR-Code प्रकार। |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | QR कोड बार की अग्रभूमि रंग; इस गुण का उपयोग करने से सत्यापन समस्याएँ हो सकती हैं, इसलिए इसे सावधानी से उपयोग करें। |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की ऊँचाई माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर) में; देखें `MeasureType` SizeMeasureType। |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | दस्तावेज़ पृष्ठ पर QR कोड का क्षैतिज संरेखण। |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | QR कोड तत्वों और परिणाम छवि की सीमाओं के बीच की जगह। |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की बाएँ X स्थिति माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर) में। |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | बाएँ और ऊपर गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | QR-code लोगो छवि फ़ाइल नाम। |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | QR-code लोगो छवि स्ट्रीम। |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | डिफ़ॉल्ट रूप से छवि और दस्तावेज़ किनारों के बीच निर्दिष्ट स्थान (यदि क्षैतिज या लंबवत संरेखण निर्दिष्ट किया गया हो तो काम करता है)। |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | मार्जिन माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | दस्तावेज़ पृष्ठ पर रखी गई हस्ताक्षर की QR-Code छवि सामग्री प्राप्त करने के लिए फ़्लैग। |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | `return_content` गुण सक्षम होने पर QR‑Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार। |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | घड़ी की दिशा में डिग्री में घूर्णन कोण। |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की शीर्ष Y स्थिति माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर) में। इकाई `LocationMeasureType` गुण द्वारा `MeasureType` प्रकार की परिभाषित होती है। |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | QR कोड हस्ताक्षर की पारदर्शिता। मान 0.0 से 1.0 तक होता है, डिफ़ॉल्ट 0 के साथ। |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | दस्तावेज़ पृष्ठ पर छवि का लंबवत संरेखण। |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की चौड़ाई माप मानों (पिक्सेल, प्रतिशत, या `MeasureType` द्वारा परिभाषित मिलीमीटर) में। |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | हस्ताक्षर सभी दस्तावेज़ पृष्ठों पर रखा जाएगा। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | अतिरिक्त हस्ताक्षर रूप। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | हस्ताक्षर पृष्ठभूमि सेटिंग्स। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | सीमा सेटिंग्स। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | हस्ताक्षर विकल्पों का दस्तावेज़ प्रकार (`DocumentType`)। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | हस्ताक्षर एक्सटेंशन। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | हस्ताक्षर का फ़ॉन्ट। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | पाठ हस्ताक्षर रखने के लिए टेक्स्ट फ़ॉर्म फ़ील्ड का शीर्षक। केवल तब उपयोग किया जा सकता है जब `signature_implementation` को `TextSignatureImplementation.FORM_FIELD` पर सेट किया गया हो। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | टेक्स्ट हस्ताक्षर रखने के लिए फ़ॉर्म फ़ील्ड का प्रकार। यह प्रॉपर्टी केवल तब लागू होती है जब `signature_implementation` को `TextSignatureImplementation.FORM_FIELD` (अर्थात् TextToFormField) पर सेट किया गया हो। डिफ़ॉल्ट मान `FormTextFieldType.ALL_TEXT_TYPES` है। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | क्रिप्टोग्राफिक संचालन के लिए उपयोग किया जाने वाला हैश एल्गोरिद्म। केवल PDF फ़ाइलों में डिजिटल हस्ताक्षरों के लिए समर्थित। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | मूल गुण। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | आकार स्थिति निर्धारित करती है कि दस्तावेज़ लेआउट में आकार कहाँ प्रस्तुत किया जाना चाहिए। केवल Word दस्तावेज़ों के लिए उपलब्ध। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | पाठ रखने के लिए आकार का प्रकार। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | हस्ताक्षर का अद्वितीय आईडी, जिसे सत्यापन विकल्पों में उपयोग किया जा सकता है और केवल PDF दस्तावेज़ों के लिए समर्थित है। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | टेक्स्ट सिग्नेचर इम्प्लीमेंटेशन का प्रकार। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिला) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | हस्ताक्षर प्रकार (`SignatureType`)। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | सिग्नेचर का टेक्स्ट। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिला) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | सिग्नेचर के भीतर टेक्स्ट का क्षैतिज संरेखण, केवल इमेज और एनोटेशन सिग्नेचर इम्प्लीमेंटेशन्स के लिए समर्थित (देखें `TextSignatureImplementation` SignatureImplementation प्रॉपर्टी)। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिला) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | सिग्नेचर के भीतर टेक्स्ट का लंबवत संरेखण। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिला) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | टेक्स्ट हस्ताक्षर की Z-ऑर्डर स्थिति, जो ओवरलैपिंग हस्ताक्षरों के प्रदर्शन क्रम को निर्धारित करती है। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # पाठ और QR कोड प्रकार को कंस्ट्रक्टर में पास करें
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # पृष्ठ के निचले दाएँ कोने में QR कोड रखें
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # मॉड्यूल रंग, पृष्ठभूमि, और अंदर कुछ जगह के साथ बिंदुदार सीमा
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
`QrCodeSignOptions` का उपयोग करने वाले कार्य गाइड:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
