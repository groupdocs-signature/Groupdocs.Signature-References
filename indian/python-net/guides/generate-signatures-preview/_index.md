---
title: "हस्ताक्षर पूर्वावलोकन उत्पन्न करें"
linkTitle: "Generate signatures preview"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह विषय समझाता है कि GroupDocs.Signature for Python via .NET द्वारा Python में विभिन्न विकल्पों के साथ दस्तावेज़ हस्ताक्षर पूर्वावलोकन कैसे उत्पन्न किया जाए।"
type: docs
url: /hi/python-net/guides/generate-signatures-preview/
is_root: false
weight: 120
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) class to generate an image of a signature before it is placed on a document - for example, to show a user what a text, barcode or QR code signature will look like.

GroupDocs.Signature के साथ हस्ताक्षर पूर्वावलोकन उत्पन्न करने के चरण यहाँ हैं:

* Create the sign options that describe the signature, for example [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) or [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/). No document is needed.
* Instantiate the [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) object with:
* the sign options;
* a function that creates the stream for the signature image (see [CreateSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createsignaturestream/));
* image preview format - PNG / JPEG / BMP / GIF / SVG (PNG by default),
* an optional `signature_id` that tells the functions which signature they are handling.

create फ़ंक्शन द्वारा लौटाया गया स्ट्रीम स्वचालित रूप से बंद हो जाता है जैसे ही हस्ताक्षर छवि लिखी जाती है: फ़ाइल बंद हो जाती है, और एक `io.BytesIO` पहले से ही पूरी छवि रखता है। यदि आपको तैयार छवि को प्रोसेस करने या संसाधनों को स्वयं साफ़ करने की आवश्यकता है, तो एक रिलीज़ फ़ंक्शन को अतिरिक्त तर्क के रूप में पास करें (देखें [ReleaseSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasesignaturestream/))।

* Call the static `generate_signature_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) to it.

## CreateSignatureStream delegate implementation

GroupDocs.Signature [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) ऑब्जेक्ट के साथ create फ़ंक्शन को कॉल करता है और लौटाए गए स्ट्रीम में हस्ताक्षर छवि लिखता है: एक लिखने योग्य फ़ाइल ऑब्जेक्ट, एक `io.BytesIO`, या एक .NET स्ट्रीम।

```python
def create_signature_stream(preview_options):
    # छवि का नाम प्रीव्यू विकल्पों में सेट किए गए signature_id के अनुसार रखें
    return open(f"{preview_options.signature_id}.png", "wb")
```

## ReleaseSignatureStream delegate implementation

रिलीज़ फ़ंक्शन वही प्रीव्यू विकल्प और वही ऑब्जेक्ट प्राप्त करता है जो create फ़ंक्शन ने लौटाया था। जब यह कॉल किया जाता है, तब छवि पूरी हो चुकी होती है।

```python
def release_signature_stream(preview_options, signature_stream):
    # signature_stream वह ऑब्जेक्ट है जो create_signature_stream ने लौटाया था
    print(f"Image file {signature_stream.name} is ready for preview")
```

## Generate signature preview to an image file

{{< tabs \"generate_signature_preview_to_file\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.pydrawing import Color
from groupdocs.signature.domain import SignatureFont
from groupdocs.signature.options import PreviewSignatureOptions, TextSignOptions

def create_signature_stream(preview_options):
    # नीचे सेट किए गए signature_id के अनुसार छवि का नाम रखें
    return open(f"{preview_options.signature_id}.png", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"Image file {signature_stream.name} is ready for preview")

def generate_signature_preview_to_file():
    # हस्ताक्षर को ठीक उसी तरह वर्णित करें जैसे आप साइनिंग के लिए करेंगे
    sign_options = TextSignOptions("John Smith")
    sign_options.width = 200
    sign_options.height = 50
    sign_options.fore_color = Color.dark_blue
    font = SignatureFont()
    font.family_name = "Arial"
    font.size = 24
    sign_options.font = font

    # प्रीव्यू विकल्प ऑब्जेक्ट बनाएं
    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
    preview_options.signature_id = "text_signature"
    preview_options.preview_format = PreviewSignatureOptions.PreviewFormats.PNG

    # पूर्वावलोकन उत्पन्न करें; कोई दस्तावेज़ शामिल नहीं है
    Signature.generate_signature_preview(preview_options)

if __name__ == "__main__":
    generate_signature_preview_to_file()
```
{{< /tab >}}
{{< tab \"text_signature.png\" >}}
```text
Binary file (PNG, 983 bytes)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_file/text_signature.png)
{{< /tab >}}
{{< /tabs >}}

## Generate signature preview to a memory stream

create फ़ंक्शन एक `io.BytesIO` लौटा सकता है। जब `generate_signature_preview` लौटता है, तो बफ़र पूरी छवि रखता है, जिसे संग्रहीत या कहीं और भेजने के लिए तैयार है।

{{< tabs \"generate_signature_preview_to_memory\" >}}
{{< tab "Python" >}}
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
{{< /tab >}}
{{< tab \"generate-signature-preview-to-memory.txt\" >}}
```text
QR code preview: 918 bytes, PNG image: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_memory/generate-signature-preview-to-memory.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate previews of several signatures in different formats

फ़ंक्शनों की एक जोड़ी किसी भी संख्या में पूर्वावलोकन सेवा दे सकती है: `signature_id` उन्हें बताता है कि वे कौन सा हस्ताक्षर संभाल रहे हैं, और `preview_format` छवि प्रकार चुनता है। बिना लाइसेंस के, SVG फ़ॉर्मेट केवल Code39 बारकोड के लिए उपलब्ध है।

{{< tabs \"generate_signature_previews_in_different_formats\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, QrCodeTypes
from groupdocs.signature.options import BarcodeSignOptions, PreviewSignatureOptions, QrCodeSignOptions

FORMATS = PreviewSignatureOptions.PreviewFormats

def create_signature_stream(preview_options):
    extension = preview_options.preview_format.name.lower()
    return open(f"{preview_options.signature_id}.{extension}", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"{preview_options.signature_id}: {signature_stream.name}")

def generate_signature_previews_in_different_formats():
    signatures = [
        ("barcode", BarcodeSignOptions("123456789012", BarcodeTypes.CODE128), FORMATS.JPEG),
        ("qr_code", QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR), FORMATS.GIF),
        ("barcode_vector", BarcodeSignOptions("GROUPDOCS", BarcodeTypes.CODE39), FORMATS.SVG),
    ]
    for signature_id, sign_options, preview_format in signatures:
        preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
        preview_options.signature_id = signature_id
        preview_options.preview_format = preview_format
        Signature.generate_signature_preview(preview_options)

if __name__ == "__main__":
    generate_signature_previews_in_different_formats()
```
{{< /tab >}}
{{< tab \"generate-signature-previews-in-different-formats-outputs.zip\" >}}
```text
barcode.jpeg (8 KB)
barcode_vector.svg (3 KB)
qr_code.gif (4 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_previews_in_different_formats/generate-signature-previews-in-different-formats-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

PDF, Word, Excel, PowerPoint, और अन्य दस्तावेज़ों पर हस्ताक्षर करने के लिए आप ऑनलाइन ऐप्स **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** से उपयोग कर सकते हैं।
