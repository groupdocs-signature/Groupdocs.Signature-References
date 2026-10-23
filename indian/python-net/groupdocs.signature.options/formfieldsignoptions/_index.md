---
title: "FormFieldSignOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "PDF दस्तावेज़ों के लिए FormField हस्ताक्षर विकल्पों को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

PDF दस्तावेज़ों के लिए FormField हस्ताक्षर विकल्पों को दर्शाता है।

PDF फ़ाइलों में फ़ॉर्म फ़ील्ड हस्ताक्षर बनाने या अपडेट करने के विकल्प प्रदान करता है।

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

FormFieldSignOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | PdfFormFieldSignOptions क्लास का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | PdfFormFieldSignOptions क्लास का एक नया उदाहरण FormField हस्ताक्षर के साथ आरंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की ऊँचाई माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर) में; देखें `MeasureType` SizeMeasureType। |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | दस्तावेज़ पृष्ठ पर छवि का क्षैतिज संरेखण। |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की बायाँ X स्थिति माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर) में। |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | छवि और दस्तावेज़ किनारों के बीच डिफ़ॉल्ट अंतराल (जब क्षैतिज या ऊर्ध्वाधर संरेखण सेट हो तो लागू होता है)। |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | मार्जिन माप प्रकार (पिक्सेल, प्रतिशत, या मिलीमीटर)। |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | घड़ी की दिशा में मापा गया घूर्णन कोण। |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | हस्ताक्षर का FormField। |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की शीर्ष Y स्थिति माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर) में है। स्थान माप प्रकार के लिए `MeasureType` देखें। |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | फ़ॉर्म फ़ील्ड हस्ताक्षर की पारदर्शिता। मान 0.0 से 1.0 तक होता है, डिफ़ॉल्ट 0 के साथ। |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | दस्तावेज़ पृष्ठ पर छवि का लंबवत संरेखण। |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की चौड़ाई माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में; देखें `MeasureType` SizeMeasureType। |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | हस्ताक्षर सभी दस्तावेज़ पृष्ठों पर रखा जाएगा। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | अतिरिक्त हस्ताक्षर रूप। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | हस्ताक्षर पृष्ठभूमि सेटिंग्स। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | सीमा सेटिंग्स। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | हस्ताक्षर विकल्पों का दस्तावेज़ प्रकार (`DocumentType`)। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | हस्ताक्षर एक्सटेंशन। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | हस्ताक्षर का फ़ॉन्ट। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिली) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | हस्ताक्षर का अग्र रंग। ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) से विरासत में मिला) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
