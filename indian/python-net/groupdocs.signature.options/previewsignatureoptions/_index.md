---
title: "PreviewSignatureOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "सिग्नेचर प्रीव्यू विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/previewsignatureoptions/
is_root: false
weight: 450
---


## PreviewSignatureOptions class

सिग्नेचर प्रीव्यू विकल्पों का प्रतिनिधित्व करता है।

PreviewSignatureOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream) | एक PreviewSignatureOptions इंस्टेंस को प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream-release_signature_stream) | एक PreviewSignatureOptions ऑब्जेक्ट को प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/preview_format/) | पूर्वावलोकन छवियों का फ़ॉर्मेट। |
| [sign_options](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/sign_options/) | प्रिव्यू उत्पन्न करने के लिए सिग्नेचर विकल्प। |
| [signature_id](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/signature_id/) | सिग्नेचर को अलग करने वाला अद्वितीय मान। |

### उदाहरण

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # फ़ाइल के बजाय बफ़र में इमेज लिखें
        return image

    sign_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
    sign_options.width = 120
    sign_options.height = 120

    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream)
    Signature.generate_signature_preview(preview_options)

    data = image.getvalue()
    print(f"QR code preview: {len(data)} bytes, PNG image: {data.startswith(b'\\x89PNG')}")
```

### Guides
`PreviewSignatureOptions` का उपयोग करने वाले टास्क गाइड्स:

* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
