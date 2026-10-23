---
title: "ImageSignOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "इमेज सिग्नेचर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

इमेज सिग्नेचर विकल्पों का प्रतिनिधित्व करता है।

और अधिक जानें:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

ImageSignOptions प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | डिफ़ॉल्ट मानों के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | ImageSignOptions को एक इमेज फ़ाइल के साथ इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | इमेज स्ट्रीम के साथ एक नया ImageSignOptions इंस्टेंस इनिशियलाइज़ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | आंतरिक संसाधनों को साफ़ करता है। |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Base64 स्ट्रिंग से पूर्वनिर्धारित इमेज के साथ नया ImageSignOptions इंस्टेंस बनाता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | इमेज हस्ताक्षर के लिए बॉर्डर सेटिंग्स। |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में; देखें `MeasureType` SizeMeasureType। |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | हस्ताक्षर छवि का फ़ाइल पथ, केवल तब उपयोग किया जाता है जब `image_stream` निर्दिष्ट नहीं किया गया हो। |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | हस्ताक्षर छवि स्ट्रीम। यदि निर्दिष्ट किया गया है, तो यह हमेशा ImageFilePath के बजाय उपयोग की जाती है। |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | हस्ताक्षर का बायां X स्थिति दस्तावेज़ पृष्ठ पर माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में। यह तब काम करता है जब क्षैतिज संरेखण निर्दिष्ट नहीं है। स्थान माप प्रकार के लिए `MeasureType` देखें। |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | बाएँ और ऊपर गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | हस्ताक्षर और दस्तावेज़ किनारों के बीच का अंतराल। यह केवल तब काम करता है जब क्षैतिज या ऊर्ध्वाधर संरेखण निर्दिष्ट हो। |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | दस्तावेज़ पर छवि रखने के लिए क्षेत्र का आयत। |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | आकार की स्थिति निर्धारित करती है कि दस्तावेज़ लेआउट में आकार कहाँ प्रस्तुत किया जाना चाहिए। केवल Word दस्तावेज़ों के लिए उपलब्ध। |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | हस्ताक्षर का शीर्ष Y स्थिति दस्तावेज़ पृष्ठ पर माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में, जैसा कि `MeasureType` LocationMeasureType द्वारा परिभाषित है। यह तब काम करता है जब ऊर्ध्वाधर संरेखण निर्दिष्ट नहीं है। |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | हस्ताक्षर की पारदर्शिता, 0.0 (अस्पष्ट) से 1.0 (स्पष्ट) तक, डिफ़ॉल्ट 0 (अस्पष्ट) है। |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का ऊर्ध्वाधर संरेखण। |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में, `MeasureType` आकार माप प्रकार। |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # इमेज फ़ाइल के साथ इमेज सिग्नेचर विकल्प बनाएं
        options = ImageSignOptions("signature.jpg")
        # सिग्नेचर की स्थिति और आकार सेट करें
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
`ImageSignOptions` का उपयोग करने वाले टास्क गाइड:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
