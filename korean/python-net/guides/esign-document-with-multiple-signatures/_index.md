---
title: "다중 서명이 포함된 eSign 문서"
linkTitle: "Multiple Types eSign"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 문서는 GroupDocs.Signature for Python via .NET API를 사용하여 다양한 유형의 여러 서명으로 문서를 서명하는 방법을 설명합니다."
type: docs
url: /ko/python-net/guides/esign-document-with-multiple-signatures/
is_root: false
weight: 80
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) allows signing a document with several signatures simultaneously and even apply signatures of different types to the same document.

이 작업은 다음과 같이 간단합니다:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path or stream as a constructor parameter.
* Instantiate all required sign options objects depending on signature type:
    * [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) - for Barcode signatures;
    * [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) - for Digital signatures;
    * [FormFieldSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/formfieldsignoptions) - for Form-field signatures;
    * [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) - for Image signatures;
    * [MetadataSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/metadatasignoptions) - for Metadata signatures;
    * [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) - for QR-code signatures
    * [StampSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/stampsignoptions) - for Stamp signatures;
    * [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) - for Text signatures.
* Fill the collection with sign options from the previous step.  
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the collection of sign options to it.

아래 코드 스니펫은 Python을 사용하여 PDF 문서를 동시에 여러 서명으로 전자 서명하는 방법을 보여줍니다:

{{< tabs \"sign_with_multiple_signatures\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import (
    BarcodeSignOptions, DigitalSignOptions, QrCodeSignOptions, TextSignOptions)
from groupdocs.signature.domain import BarcodeTypes, QrCodeTypes

def sign_with_multiple_signatures():
    with Signature("sample.pdf") as signature:
        # 텍스트 서명 옵션 정의
        text_options = TextSignOptions("This is test message")
        text_options.left = 100
        text_options.top = 360
        text_options.width = 200
        text_options.height = 30

        # 바코드 서명 옵션 정의
        barcode_options = BarcodeSignOptions("123456")
        barcode_options.encode_type = BarcodeTypes.CODE128
        barcode_options.left = 100
        barcode_options.top = 420
        barcode_options.width = 200
        barcode_options.height = 60

        # QR 코드 서명 옵션 정의
        qrcode_options = QrCodeSignOptions("JohnSmith")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.left = 100
        qrcode_options.top = 520
        qrcode_options.width = 100
        qrcode_options.height = 100

        # 인증서와 외관 이미지를 포함한 디지털 서명 옵션 정의
        digital_options = DigitalSignOptions("certificate.pfx")
        digital_options.password = "1234567890"
        digital_options.image_file_path = "signature.jpg"
        digital_options.left = 350
        digital_options.top = 520
        digital_options.width = 160
        digital_options.height = 100

        # 서명 옵션 목록을 사용하여 문서에 서명
        list_options = [text_options, barcode_options, qrcode_options, digital_options]
        result = signature.sign("signed_multiple.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은 이 예제에서 사용된 샘플 파일입니다. [여기](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf)를 클릭하여 다운로드하십시오.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx`은 이 예제에서 사용된 샘플 인증서입니다 (비밀번호 `1234567890`). [여기](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/certificate.pfx)를 클릭하여 다운로드하십시오.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg`은 이 예제에서 사용된 샘플 파일입니다. [여기](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/signature.jpg)를 클릭하여 다운로드하십시오.

{{< /tab >}}
{{< tab \"signed_multiple.pdf\" >}}
```text
Binary file (PDF, 740 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures/signed_multiple.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Multiple Signatures Example

다음은 다양한 스타일과 위치로 여러 서명을 추가하는 방법을 보여주는 보다 고급 예제입니다. 각 서명은 정렬 및 페이지 가장자리와의 여백을 기준으로 배치됩니다:

{{< tabs \"sign_with_multiple_signatures_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions, QrCodeSignOptions, TextSignOptions
from groupdocs.signature.domain import (
    HorizontalAlignment, Padding, QrCodeTypes, SignatureFont, VerticalAlignment)

def sign_with_multiple_signatures_advanced():
    with Signature("sample.pdf") as signature:
        # 페이지 헤더 아래 오른쪽 상단에 굵은 텍스트 서명
        text_options = TextSignOptions("Approved by John Smith")
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        text_options.font = font
        text_options.width = 280
        text_options.height = 40
        text_options.vertical_alignment = VerticalAlignment.TOP
        text_options.horizontal_alignment = HorizontalAlignment.RIGHT
        text_options.margin = Padding(top=170, right=20)

        # 왼쪽 하단 모서리에 스탬프 이미지
        image_options = ImageSignOptions("stamp.png")
        image_options.width = 100
        image_options.height = 100
        image_options.vertical_alignment = VerticalAlignment.BOTTOM
        image_options.horizontal_alignment = HorizontalAlignment.LEFT
        image_options.margin = Padding(left=20, bottom=20)

        # 오른쪽 하단 모서리에 QR 코드
        qrcode_options = QrCodeSignOptions("https://www.example.com/verify")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.width = 100
        qrcode_options.height = 100
        qrcode_options.vertical_alignment = VerticalAlignment.BOTTOM
        qrcode_options.horizontal_alignment = HorizontalAlignment.RIGHT
        qrcode_options.margin = Padding(right=20, bottom=20)

        # 서명 옵션 목록을 사용하여 문서에 서명
        list_options = [text_options, image_options, qrcode_options]
        result = signature.sign("signed_multiple_advanced.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은 이 예제에서 사용된 샘플 파일입니다. [여기](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf)를 클릭하여 다운로드하십시오.

{{< /tab >}}
{{< tab \"stamp.png\" >}}

`stamp.png`은 이 예제에서 사용된 샘플 파일입니다. [여기](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/stamp.png)를 클릭하여 다운로드하십시오.

{{< /tab >}}
{{< tab \"signed_multiple_advanced.pdf\" >}}
```text
Binary file (PDF, 178 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures_advanced/signed_multiple_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
이 가이드는 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net)를 사용하여 문서에 여러 유형의 전자 서명(예: 텍스트, 바코드, 이미지)을 적용하는 방법을 보여줍니다. 서로 다른 서명 유형을 결합하고, 각각을 구성하며, 여러 서명 스타일이 적용된 문서를 저장하는 방법을 설명합니다.

## More Resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 온라인 앱을 사용할 수 있습니다.
