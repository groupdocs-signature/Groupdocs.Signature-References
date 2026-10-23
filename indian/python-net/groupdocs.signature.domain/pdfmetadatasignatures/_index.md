---
title: "PdfMetadataSignatures क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "PDF दस्तावेज़ मेटाडेटा हस्ताक्षर विकल्पों के लिए मानक मेटाडेटा हस्ताक्षर शामिल करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/pdfmetadatasignatures/
is_root: false
weight: 450
---


## PdfMetadataSignatures class

PDF दस्तावेज़ मेटाडेटा हस्ताक्षर विकल्पों के लिए मानक मेटाडेटा हस्ताक्षर शामिल करता है।

PdfMetadataSignatures प्रकार निम्नलिखित सदस्य उजागर करता है:

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [AUTHOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/author/) | Pdf दस्तावेज़ लेखक मेटाडेटा। |
| [CREATE_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/create_date/) | Pdf दस्तावेज़ निर्माण तिथि मेटाडेटा सिग्नेचर। |
| [METADATA_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/metadata_date/) | Pdf दस्तावेज़ मेटाडेटा तिथि जानकारी। |
| [CREATOR_TOOL](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator_tool/) | Pdf दस्तावेज़ निर्माण टूल मेटाडेटा सिग्नेचर। |
| [MODIFY_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/modify_date/) | Pdf दस्तावेज़ संशोधित तिथि मेटाडेटा प्रॉपर्टी। |
| [PRODUCER](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/producer/) | Pdf दस्तावेज़ प्रोड्यूसर मेटाडेटा प्रॉपर्टी। |
| [ENTRY](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/entry/) | Pdf दस्तावेज़ एंट्री मेटाडेटा प्रॉपर्टी। |
| [KEYWORDS](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/keywords/) | Pdf दस्तावेज़ निर्माता मेटाडेटा प्रॉपर्टी |
| [TITLE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/title/) | Pdf दस्तावेज़ शीर्षक मेटाडेटा प्रॉपर्टी |
| [SUBJECT](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/subject/) | Pdf दस्तावेज़ विषय मेटाडेटा प्रॉपर्टी। |
| [DESCRIPTION](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/description/) | Pdf दस्तावेज़ विवरण मेटाडेटा प्रॉपर्टी। |
| [CREATOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator/) | Pdf दस्तावेज़ निर्माता मेटाडेटा प्रॉपर्टी। |

### उदाहरण

```python
from datetime import datetime, timedelta

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures


def sign_pdf_standard():
    with Signature("sample.pdf") as signature:
        options = MetadataSignOptions()

        now = datetime.now()
        signatures = [
            PdfMetadataSignatures.AUTHOR.clone("Mr.Scherlock Holmes"),
            PdfMetadataSignatures.CREATE_DATE.clone(now - timedelta(days=1)),
            PdfMetadataSignatures.METADATA_DATE.clone(now - timedelta(days=2)),
            PdfMetadataSignatures.CREATOR_TOOL.clone("GD.Signature-Test"),
            PdfMetadataSignatures.MODIFY_DATE.clone(now - timedelta(days=13)),
            PdfMetadataSignatures.PRODUCER.clone("GroupDocs-Producer"),
            PdfMetadataSignatures.ENTRY.clone("Signature"),
            PdfMetadataSignatures.KEYWORDS.clone("GroupDocs, Signature, Metadata, Creation Tool"),
            PdfMetadataSignatures.TITLE.clone("Metadata Example"),
            PdfMetadataSignatures.SUBJECT.clone("Metadata Test Example"),
            PdfMetadataSignatures.DESCRIPTION.clone("Metadata Test example description"),
            PdfMetadataSignatures.CREATOR.clone("GroupDocs.Signature"),
        ]

        options.signatures.add_range(signatures)
```

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
