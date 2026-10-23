---
title: "TextSignOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "टेक्स्ट हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

टेक्स्ट हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

और अधिक जानें

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

TextSignOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | डिफ़ॉल्ट मानों के साथ TextSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | टेक्स्ट के साथ TextSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | हस्ताक्षर पृष्ठभूमि सेटिंग्स। |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | बॉर्डर सेटिंग्स। |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | हस्ताक्षर का फ़ॉन्ट। |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | हस्ताक्षर का अग्र रंग। |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | टेक्स्ट हस्ताक्षर को रखने के लिए टेक्स्ट फ़ॉर्म फ़ील्ड का शीर्षक। इसे केवल तब उपयोग किया जा सकता है जब `signature_implementation` को `TextSignatureImplementation.FORM_FIELD` पर सेट किया गया हो। |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | टेक्स्ट सिग्नेचर रखने के लिए फ़ॉर्म फ़ील्ड का प्रकार। यह प्रॉपर्टी केवल तभी लागू होती है जब `signature_implementation` को `TextSignatureImplementation.FORM_FIELD` (अर्थात् TextToFormField) पर सेट किया गया हो। डिफ़ॉल्ट मान `FormTextFieldType.ALL_TEXT_TYPES` है। |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | दस्तावेज़ पृष्ठ पर सिग्नेचर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में। इकाई `SizeMeasureType` प्रॉपर्टी द्वारा निर्धारित की जाती है। |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | दस्तावेज़ पृष्ठ पर सिग्नेचर की बायीं X स्थिति माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में, जैसा कि `MeasureType` LocationMeasureType प्रॉपर्टी द्वारा परिभाषित है। यह तब काम करता है जब क्षैतिज संरेखण निर्दिष्ट नहीं हो। |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | `left` और `top` प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | सिग्नेचर और दस्तावेज़ किनारों के बीच का अंतराल। यह केवल तब लागू होता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट किया गया हो। |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | मूल एट्रिब्यूट। |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | आकार की स्थिति निर्धारित करती है कि दस्तावेज़ लेआउट में आकार कहाँ प्रस्तुत किया जाना चाहिए। केवल Word दस्तावेज़ों के लिए उपलब्ध। |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | टेक्स्ट रखने के लिए आकार का प्रकार। |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | सिग्नेचर की अनूठी ID, जिसे सत्यापन विकल्पों में उपयोग किया जा सकता है और केवल PDF दस्तावेज़ों के लिए समर्थित है। |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | टेक्स्ट सिग्नेचर कार्यान्वयन का प्रकार। |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | सिग्नेचर का टेक्स्ट। |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | सिग्नेचर के भीतर टेक्स्ट का क्षैतिज संरेखण, केवल Image और Annotation सिग्नेचर कार्यान्वयनों के लिए समर्थित है (देखें `TextSignatureImplementation` SignatureImplementation प्रॉपर्टी)। |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | हस्ताक्षर के भीतर पाठ का लंबवत संरेखण। |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | दस्तावेज़ पृष्ठ पर सिग्नेचर की शीर्ष Y स्थिति, माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर) में व्यक्त। |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | सिग्नेचर की पारदर्शिता, 0.0 (अपारदर्शी) और 1.0 (स्पष्ट) के बीच का फ्लोट। डिफ़ॉल्ट 0.0 (अपारदर्शी) है। |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का ऊर्ध्वाधर संरेखण। |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | दस्तावेज़ पृष्ठ पर सिग्नेचर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में; देखें `MeasureType` `SizeMeasureType` प्रॉपर्टी। |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | हस्ताक्षर सभी दस्तावेज़ पृष्ठों पर रखा जाएगा। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | अतिरिक्त हस्ताक्षर रूप। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | हस्ताक्षर विकल्पों का दस्तावेज़ प्रकार (`DocumentType`)। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | हस्ताक्षर एक्सटेंशन। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | क्रिप्टोग्राफिक संचालन के लिए उपयोग किया जाने वाला हैश एल्गोरिद्म। केवल PDF फ़ाइलों में डिजिटल हस्ताक्षरों के लिए समर्थित। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | हस्ताक्षर प्रकार (`SignatureType`)। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | टेक्स्ट हस्ताक्षर की Z-ऑर्डर स्थिति, जो ओवरलैपिंग हस्ताक्षरों के प्रदर्शन क्रम को निर्धारित करती है। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
`TextSignOptions` का उपयोग करने वाले टास्क गाइड्स:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
