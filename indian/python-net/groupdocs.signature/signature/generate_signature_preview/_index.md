---
title: "generate_signature_preview मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दिए गए SignOptions के आधार पर हस्ताक्षर का पूर्वावलोकन उत्पन्न करता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

दिए गए SignOptions के आधार पर हस्ताक्षर का पूर्वावलोकन उत्पन्न करता है।

हस्ताक्षरों के प्रीव्यू कैसे बनाएं, इस बारे में अधिक जानें:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | दिए गए SignOptions के साथ प्रीव्यू हस्ताक्षर। |

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
    is_png = data.startswith(b"\x89PNG")
    print(f"QR code preview: {len(data)} bytes, PNG image: {is_png}")

if __name__ == "__main__":
    generate_signature_preview_to_memory()
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
