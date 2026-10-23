---
title: "DigitalSignOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिजिटल हस्ताक्षर विकल्पों को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

डिजिटल हस्ताक्षर विकल्पों को दर्शाता है।

और अधिक जानें

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

DigitalSignOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | डिफ़ॉल्ट मानों के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | सर्टिफ़िकेट फ़ाइल के साथ नया DigitalSignOptions इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | सर्टिफ़िकेट स्ट्रीम के साथ नया DigitalSignOptions इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | सर्टिफ़िकेट फ़ाइल और एक एपीयरेंस इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | सर्टिफ़िकेट फ़ाइल और एक एपीयरेंस इमेज स्ट्रीम के साथ DigitalSignOptions का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | सर्टिफ़िकेट स्ट्रीम और एक एपीयरेंस इमेज फ़ाइल के साथ DigitalSignOptions का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | सर्टिफ़िकेट स्ट्रीम और एक एपीयरेंस इमेज स्ट्रीम के साथ नया DigitalSignOptions इंस्टेंस इनिशियलाइज़ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | आंतरिक संसाधनों को साफ़ करता है। ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) से विरासत में मिला) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Base64 स्ट्रिंग से पूर्वनिर्धारित इमेज के साथ नया ImageSignOptions इंस्टेंस बनाता है। ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) से विरासत में मिला) |

### गुण
| गुण | विवरण |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | सर्टिफ़िकेट जिसकी वैधता अवधि समाप्त हो गई है, उसके साथ साइन करने की अनुमति देने वाला फ़्लैग। डिफ़ॉल्ट मान False है; समाप्त सर्टिफ़िकेट के साथ साइन करने पर `GroupDocsSignatureException` उत्पन्न होता है और दस्तावेज़ साइन नहीं होता। |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | सर्टिफ़िकेट जिसकी वैधता अवधि अभी शुरू नहीं हुई है, उसके साथ साइन करने की अनुमति देने वाला फ़्लैग। डिफ़ॉल्ट मान False है; ऐसे सर्टिफ़िकेट के साथ साइन करने पर `GroupDocsSignatureException` उत्पन्न होता है और दस्तावेज़ साइन नहीं होता। |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | डिजिटल सर्टिफ़िकेट फ़ाइल पथ। |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | डिजिटल प्रमाणपत्र स्ट्रीम। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा CertificateFilePath के बजाय उपयोग किया जाता है। |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | हस्ताक्षर संपर्क। |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | दस्तावेज़ को साइन करने के लिए उपयोग किया जाने वाला कस्टम हैश साइनिंग फ़ंक्शन, जो उपयोगकर्ताओं को अपनी स्वयं की डिजिटल साइनिंग लॉजिक लागू करने की अनुमति देता है। |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की ऊँचाई माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर; देखें `MeasureType`) में। |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | दस्तावेज़ पृष्ठ पर छवि का क्षैतिज संरेखण। |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की बायाँ X स्थिति माप इकाइयों (पिक्सेल, प्रतिशत, या `MeasureType.location_measure_type` द्वारा परिभाषित मिलीमीटर) में। |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | हस्ताक्षर स्थान। |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | डिफ़ॉल्ट रूप से छवि और दस्तावेज़ किनारों के बीच निर्दिष्ट स्थान (जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो तो लागू होता है)। |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | मार्जिन माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | डिजिटल प्रमाणपत्र का पासवर्ड। |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | हस्ताक्षर का कारण। |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | घड़ी की दिशा में घूर्णन कोण। |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | दस्तावेज़ के लिए डिजिटल हस्ताक्षर गुण। PDF साइनिंग के लिए, उन्नत गुण एक [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/) इंस्टेंस का उपयोग करके सेट किए जा सकते हैं। |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की शीर्ष Y स्थिति माप इकाइयों (पिक्सेल, प्रतिशत, या मिलीमीटर; देखें `MeasureType` `LocationMeasureType`) में। |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | डिजिटल हस्ताक्षर की पारदर्शिता, 0.0 से 1.0 तक। डिफ़ॉल्ट 0 है। |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | LTV (लॉन्ग टर्म वैलिडेशन) वैधता फ़्लैग। |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | दस्तावेज़ पृष्ठ पर छवि का लंबवत संरेखण। |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | हस्ताक्षर की दृश्यता। |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | दस्तावेज़ पृष्ठ पर हस्ताक्षर क्षेत्र की चौड़ाई माप मानों (पिक्सेल, प्रतिशत, या मिलीमीटर) में। माप इकाई `MeasureType` द्वारा SizeMeasureType गुण के माध्यम से परिभाषित होती है। |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | XAdES प्रकार। डिफ़ॉल्ट मान None है (XAdES बंद है)। |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | हस्ताक्षर सभी दस्तावेज़ पृष्ठों पर रखा जाएगा। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | अतिरिक्त हस्ताक्षर रूप। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | छवि हस्ताक्षर के लिए बॉर्डर सेटिंग्स। (से विरासत में मिली [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | हस्ताक्षर विकल्पों का दस्तावेज़ प्रकार (`DocumentType`)। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | हस्ताक्षर एक्सटेंशन। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | क्रिप्टोग्राफिक संचालन के लिए उपयोग किया जाने वाला हैश एल्गोरिद्म। केवल PDF फ़ाइलों में डिजिटल हस्ताक्षरों के लिए समर्थित। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | हस्ताक्षर छवि का फ़ाइल पथ, केवल तब उपयोग किया जाता है जब `image_stream` निर्दिष्ट न हो। (से विरासत में मिली [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | हस्ताक्षर छवि स्ट्रीम। यदि निर्दिष्ट किया गया है, तो यह हमेशा ImageFilePath के बजाय उपयोग किया जाता है। (से विरासत में मिली [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | दस्तावेज़ पर छवि रखने के लिए क्षेत्र का आयत। (से विरासत में मिली [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | शेप पोज़िशन निर्धारित करता है कि दस्तावेज़ लेआउट में शैप कहाँ प्रस्तुत किया जाना चाहिए। केवल Word दस्तावेज़ों के लिए उपलब्ध। (से विरासत में मिली [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | हस्ताक्षर प्रकार (`SignatureType`)। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | टेक्स्ट हस्ताक्षर की Z-ऑर्डर स्थिति, जो ओवरलैपिंग हस्ताक्षरों के प्रदर्शन क्रम को निर्धारित करती है। (विरासत में मिला [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # सर्टिफ़िकेट और अपीयरेंस इमेज को कन्स्ट्रक्टर में पास करें
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # पृष्ठ पर हस्ताक्षर दिखाएँ, इस स्थिति और आकार पर
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # हस्ताक्षर में संग्रहीत जानकारी
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
`DigitalSignOptions` का उपयोग करने वाले कार्य मार्गदर्शक:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
