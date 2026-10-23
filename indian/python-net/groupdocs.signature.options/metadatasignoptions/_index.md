---
title: "MetadataSignOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "मेटाडेटा सिग्नेचर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

मेटाडेटा सिग्नेचर विकल्पों का प्रतिनिधित्व करता है।

और अधिक जानें

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

MetadataSignOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | MetadataSignOptions क्लास का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) का एक नया उदाहरण मेटाडेटा के साथ प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | मौजूदा MetadataSignature उदाहरण को संग्रह में जोड़ें। |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | दिए गए तर्कों के साथ एक नया ImageMetadataSignature बनाता है और उसे संग्रह में जोड़ता है। |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | दिए गए तर्कों के साथ एक नया PdfMetadataSignature बनाता है और उसे संग्रह में जोड़ता है। |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### गुण
| गुण | विवरण |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) का कार्यान्वयन इस विकल्प संग्रह में सभी मेटाडेटा हस्ताक्षरों को एन्क्रिप्ट करने के लिए उपयोग किया जाता है। |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | हस्ताक्षर से जुड़े मेटाडेटा हस्ताक्षर। |
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
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
