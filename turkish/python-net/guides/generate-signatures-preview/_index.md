---
title: "İmzaların önizlemesini oluştur"
linkTitle: "Generate signatures preview"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu konu, GroupDocs.Signature for Python via .NET tarafından Python'da çeşitli seçeneklerle belge imza önizlemesinin nasıl oluşturulacağını açıklar."
type: docs
url: /tr/python-net/guides/generate-signatures-preview/
is_root: false
weight: 120
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) class to generate an image of a signature before it is placed on a document - for example, to show a user what a text, barcode or QR code signature will look like.

GroupDocs.Signature ile imza önizlemesi oluşturmak için adımlar şunlardır:

* Create the sign options that describe the signature, for example [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) or [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/). No document is needed.
* Instantiate the [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) object with:
* the sign options;
* a function that creates the stream for the signature image (see [CreateSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createsignaturestream/));
* image preview format - PNG / JPEG / BMP / GIF / SVG (PNG by default),
* an optional `signature_id` that tells the functions which signature they are handling.

create fonksiyonu tarafından döndürülen akış, imza görüntüsü yazıldıktan hemen sonra otomatik olarak kapatılır: bir dosya kapanır ve `io.BytesIO` zaten tam görüntüyü tutar. Bitmiş görüntüyü işlemek veya kaynakları kendiniz temizlemek isterseniz, ek bir argüman olarak bir release fonksiyonu geçirin (bkz. [ReleaseSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasesignaturestream/)).

* Call the static `generate_signature_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) to it.

## CreateSignatureStream delegate implementation

GroupDocs.Signature, [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) nesnesiyle create fonksiyonunu çağırır ve imza görüntüsünü döndürdüğü akışa yazar: yazılabilir bir dosya nesnesi, bir `io.BytesIO` veya bir .NET akışı.

```python
def create_signature_stream(preview_options):
    # Görüntüyü, önizleme seçeneklerinde ayarlanan signature_id değerine göre adlandırın
    return open(f"{preview_options.signature_id}.png", "wb")
```

## ReleaseSignatureStream delegate implementation

Release fonksiyonu aynı önizleme seçeneklerini ve create fonksiyonunun döndürdüğü aynı nesneyi alır. Çağrıldığı anda görüntü tamamlanmıştır.

```python
def release_signature_stream(preview_options, signature_stream):
    # signature_stream, create_signature_stream tarafından döndürülen nesnedir
    print(f"Image file {signature_stream.name} is ready for preview")
```

## Generate signature preview to an image file

{{< tabs "generate_signature_preview_to_file" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.pydrawing import Color
from groupdocs.signature.domain import SignatureFont
from groupdocs.signature.options import PreviewSignatureOptions, TextSignOptions

def create_signature_stream(preview_options):
    # Görüntüyü, aşağıda ayarlanan signature_id değerine göre adlandırın
    return open(f"{preview_options.signature_id}.png", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"Image file {signature_stream.name} is ready for preview")

def generate_signature_preview_to_file():
    # İmzayı, imzalama yapacağınız gibi tam olarak tanımlayın
    sign_options = TextSignOptions("John Smith")
    sign_options.width = 200
    sign_options.height = 50
    sign_options.fore_color = Color.dark_blue
    font = SignatureFont()
    font.family_name = "Arial"
    font.size = 24
    sign_options.font = font

    # Önizleme seçenekleri nesnesi oluştur
    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
    preview_options.signature_id = "text_signature"
    preview_options.preview_format = PreviewSignatureOptions.PreviewFormats.PNG

    # Önizleme oluştur; belge dahil değildir
    Signature.generate_signature_preview(preview_options)

if __name__ == "__main__":
    generate_signature_preview_to_file()
```
{{< /tab >}}
{{< tab "text_signature.png" >}}
```text
Binary file (PNG, 983 bytes)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_file/text_signature.png)
{{< /tab >}}
{{< /tabs >}}

## Generate signature preview to a memory stream

create fonksiyonu bir `io.BytesIO` döndürebilir. `generate_signature_preview` döndüğünde, tampon tüm görüntüyü tutar ve başka bir yere kaydedilmeye ya da gönderilmeye hazırdır.

{{< tabs "generate_signature_preview_to_memory" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Görüntüyü bir dosya yerine tampon belleğe yaz.
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
{{< tab "generate-signature-preview-to-memory.txt" >}}
```text
QR code preview: 918 bytes, PNG image: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_memory/generate-signature-preview-to-memory.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate previews of several signatures in different formats

Bir fonksiyon çifti, herhangi bir sayıda önizleme için hizmet verebilir: `signature_id` hangi imzayı işlediklerini belirtir ve `preview_format` görüntü tipini seçer. Lisans olmadan, SVG formatı yalnızca Code39 barkodları için kullanılabilir.

{{< tabs "generate_signature_previews_in_different_formats" >}}
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
{{< tab "generate-signature-previews-in-different-formats-outputs.zip" >}}
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

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** adresindeki çevrimiçi uygulamaları kullanabilirsiniz.
