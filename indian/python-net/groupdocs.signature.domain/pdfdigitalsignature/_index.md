---
title: "PdfDigitalSignature क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "PDF डिजिटल हस्ताक्षर गुणों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

PDF डिजिटल हस्ताक्षर गुणों का प्रतिनिधित्व करता है।

यह PdfDigitalSignature प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | एक प्रमाणपत्र के बिना PDF डिजिटल हस्ताक्षर को प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | निर्दिष्ट X509 स्टोर का उपयोग करके PDF डिजिटल हस्ताक्षर को प्रारंभ करता है। स्टोर से पहला प्रमाणपत्र उपयोग किया जाएगा। |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | निर्दिष्ट X509 स्टोर और प्रमाणपत्र अनुक्रमणिका का उपयोग करके PDF डिजिटल हस्ताक्षर को प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | निर्दिष्ट X509 प्रमाणपत्र के साथ PDF डिजिटल हस्ताक्षर को प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | PDF डिजिटल हस्ताक्षर इंस्टेंस को क्लोन करें। |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | समानता निर्धारित करने के लिए हस्ताक्षर गुणों की तुलना करता है। |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | GetHashCode मेथड को ओवरराइड करता है। |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | सभी सिस्टम X509 प्रमाणपत्र स्टोर्स से डिजिटल हस्ताक्षर लोड करें। (विरासत में मिला [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (विरासत में मिला [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (विरासत में मिला [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (विरासत में मिला [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### गुण
| गुण | विवरण |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | हस्ताक्षरकर्ता द्वारा प्रदान की गई संपर्क जानकारी, जिससे प्राप्तकर्ता हस्ताक्षर को सत्यापित कर सके, जैसे कि फ़ोन नंबर। |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | हस्ताक्षर का CPU होस्ट नाम या भौतिक स्थान। |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | हस्ताक्षर का कारण, जैसे (I agree)। |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | फ़्लैग जो हस्ताक्षर गुणों को दिखाने या छिपाने के लिए बाध्य करता है; जब सत्य हो, तो हस्ताक्षर फ़ील्ड एक पूर्वनिर्धारित रूप स्वरूप का उपयोग करता है (उदाहरण के लिए, `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) और डिफ़ॉल्ट रूप से True रहता है। |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | PDF डिजिटल हस्ताक्षर के लिए टाइमस्टैम्प। डिफ़ॉल्ट मान None है। |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | PDF डिजिटल हस्ताक्षर का प्रकार। |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | डिजिटल हस्ताक्षर से जुड़ा X509 प्रमाणपत्र। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | प्रमाणपत्र का कस्टम स्टोर नाम। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | प्रमाणपत्र का स्टोर स्थान। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | प्रमाणपत्र का स्टोर नाम। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | हस्ताक्षर उद्देश्य टिप्पणी। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | सिग्नेचर निर्माण तिथि। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | यह संकेतक कि यह सिग्नेचर दस्तावेज़ से हटाया गया था या नहीं, दर्शाता है। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | सिग्नेचर की ऊँचाई। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | यह संकेतक कि यह घटक सिग्नेचर (`True`) है या दस्तावेज़ सामग्री (`False`)। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | डिजिटल हस्ताक्षर वैध है और दस्तावेज़ में कोई छेड़छाड़ नहीं हुई है। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | हस्ताक्षर की बाएँ स्थिति। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | हस्ताक्षर संशोधन तिथि। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | हस्ताक्षर जहाँ पाया गया, उस पृष्ठ संख्या। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | दस्तावेज़ पर हस्ताक्षर किए जाने का समय। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | हस्ताक्षर का अद्वितीय पहचानकर्ता, जो दस्तावेज़ में अपडेट या डिलीट ऑपरेशनों के माध्यम से हस्ताक्षर को संशोधित करने के लिए उपयोग किया जाता है। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | हस्ताक्षर का प्रकार। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | प्रमाणपत्र का थंबप्रिंट। (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | हस्ताक्षर की शीर्ष स्थिति। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | हस्ताक्षर की चौड़ाई। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | XAdES प्रकार ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). (inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
