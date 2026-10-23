---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "एक PreviewSignatureOptions इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

एक PreviewSignatureOptions इंस्टेंस को प्रारंभ करता है।

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sign_options | `SignOptions` | प्रिव्यू उत्पन्न करने के लिए सिग्नेचर विकल्प। |
| create_signature_stream | `CreateSignatureStream` | आउटपुट सिग्नेचर प्रिव्यू स्ट्रीम बनाने वाला डेलीगेट। |

### उदाहरण

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# प्रिव्यू इमेज प्राप्त करने के लिए मेमोरी बफ़र
preview_buffer = io.BytesIO()

def create_stream(options):
    # किसी भी प्रिव्यू जनरेशन के लिए वही बफ़र लौटाएँ
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# बफ़र में प्रिव्यू इमेज उत्पन्न करें
Signature.generate_signature_preview(preview_opts)

# उत्पन्न PNG बाइट्स तक पहुँचें
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

एक PreviewSignatureOptions ऑब्जेक्ट को प्रारंभ करता है।

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sign_options | `SignOptions` | प्रिव्यू उत्पन्न करने के लिए सिग्नेचर विकल्प। |
| create_signature_stream | `CreateSignatureStream` | एक कॉलेबल जो आउटपुट सिग्नेचर प्रिव्यू स्ट्रीम बनाता है। यह सिग्नेचर विकल्प प्राप्त करता है और एक `io.RawIOBase` (उदा., `io.BytesIO`) लौटाना चाहिए। |
| release_signature_stream | `ReleaseSignatureStream` | एक कॉलेबल जो आउटपुट सिग्नेचर प्रिव्यू स्ट्रीम को रिलीज़ करता है। यह सिग्नेचर विकल्प और स्ट्रीम प्राप्त करता है और आवश्यक सफ़ाई करता है। |

### उदाहरण

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_qr_code_image():
    result = io.BytesIO()
    qr_options = QrCodeSignOptions()
    qr_options.encode_type = QrCodeTypes.QR
    qr_options.text = "Case 148-01"

    preview_options = PreviewSignatureOptions(
        qr_options,
        lambda options: result,
        lambda options, stream: None,
    )
    Signature.generate_signature_preview(preview_options)

    with open("qr_code_result.png", "wb") as f:
        f.write(result.getvalue())
```

### संबंधित देखें
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
