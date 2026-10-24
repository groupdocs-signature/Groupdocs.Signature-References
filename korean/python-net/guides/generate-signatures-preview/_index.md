---
title: "서명 미리보기 생성"
linkTitle: "Generate signatures preview"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 항목에서는 GroupDocs.Signature for Python via .NET을 사용하여 Python에서 다양한 옵션으로 문서 서명 미리보기를 생성하는 방법을 설명합니다."
type: docs
url: /ko/python-net/guides/generate-signatures-preview/
is_root: false
weight: 120
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) class to generate an image of a signature before it is placed on a document - for example, to show a user what a text, barcode or QR code signature will look like.

다음은 GroupDocs.Signature를 사용하여 서명 미리보기를 생성하는 단계입니다:

* Create the sign options that describe the signature, for example [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) or [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/). No document is needed.
* Instantiate the [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) object with:
* the sign options;
* a function that creates the stream for the signature image (see [CreateSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createsignaturestream/));
* image preview format - PNG / JPEG / BMP / GIF / SVG (PNG by default),
* an optional `signature_id` that tells the functions which signature they are handling.

create 함수가 반환하는 스트림은 서명 이미지가 기록되는 즉시 자동으로 닫힙니다: 파일이 닫히고, `io.BytesIO`가 이미 완전한 이미지를 보유합니다. 완료된 이미지를 처리하거나 직접 리소스를 정리해야 하는 경우, 추가 인수로 릴리스 함수를 전달하십시오(참조 [ReleaseSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasesignaturestream/)).

* Call the static `generate_signature_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) to it.

## CreateSignatureStream delegate implementation

GroupDocs.Signature는 [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) 객체와 함께 create 함수를 호출하고, 반환된 스트림에 서명 이미지를 기록합니다: 쓰기 가능한 파일 객체, `io.BytesIO` 또는 .NET 스트림.

```python
def create_signature_stream(preview_options):
    # 미리보기 옵션에 설정된 signature_id를 사용하여 이미지 이름을 지정합니다
    return open(f"{preview_options.signature_id}.png", "wb")
```

## ReleaseSignatureStream delegate implementation

릴리스 함수는 동일한 미리보기 옵션과 create 함수가 반환한 동일한 객체를 받습니다. 호출 시점에 이미지는 완성되어 있습니다.

```python
def release_signature_stream(preview_options, signature_stream):
    # signature_stream은 create_signature_stream이 반환한 객체입니다
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
    # 아래에 설정된 signature_id를 사용하여 이미지 이름을 지정합니다
    return open(f"{preview_options.signature_id}.png", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"Image file {signature_stream.name} is ready for preview")

def generate_signature_preview_to_file():
    # 서명을 할 때와 같이 서명을 정확히 설명하십시오
    sign_options = TextSignOptions("John Smith")
    sign_options.width = 200
    sign_options.height = 50
    sign_options.fore_color = Color.dark_blue
    font = SignatureFont()
    font.family_name = "Arial"
    font.size = 24
    sign_options.font = font

    # 미리보기 옵션 객체 생성
    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
    preview_options.signature_id = "text_signature"
    preview_options.preview_format = PreviewSignatureOptions.PreviewFormats.PNG

    # 미리보기를 생성합니다; 문서는 포함되지 않습니다
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

create 함수는 `io.BytesIO`를 반환할 수 있습니다. `generate_signature_preview`가 반환될 때, 버퍼에는 전체 이미지가 들어 있어 저장하거나 다른 곳으로 전송할 준비가 됩니다.

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
        # 파일 대신 버퍼에 이미지를 씁니다
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

두 개의 함수 쌍으로 모든 미리보기를 처리할 수 있습니다: `signature_id`는 어떤 서명을 다루는지 알려주고, `preview_format`은 이미지 유형을 선택합니다. 라이선스가 없으면 SVG 형식은 Code39 바코드에만 사용할 수 있습니다.

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

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 온라인 앱을 사용할 수 있습니다.
