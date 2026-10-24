---
title: "바코드 서명을 사용한 전자 서명 문서"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 문서에서는 GroupDocs.Signature for Python via .NET을 사용하여 바코드 유형, 바코드 텍스트, 위치 지정, 정렬 및 기타 시각적 설정과 같은 다양한 옵션으로 문서 페이지에 Barcode 서명을 추가하는 방법을 설명합니다."
type: docs
url: /ko/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

**barcode** 또는 **bar code**는 데이터를 시각적이며 기계가 읽을 수 있는 형태로 표현하는 방법입니다. 일반적으로 barcode는 서로 다른 두께의 평행한 검은 선과 흰색 공간으로 구성된 직사각형 형태의 이미지입니다.
바코드는 빠른 식별이 필요한 다양한 분야에서 사용됩니다 - 소매점에서 구매 과정의 일부로, 창고에서 재고를 추적하기 위해, 그리고 청구서에서 회계를 지원하는 등 여러 용도로 활용됩니다.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

바코드는 제조일 및 유통기한, 제조업체명, 원산지, 제품 가격 등 제품 관련 데이터를 저장할 수 있게 해줍니다. 다양한 기업이 필요에 따라 서로 다른 숫자와 막대 조합을 사용하기 때문에 현재 바코드 유형이 많이 존재합니다. 문서 서명 관점에서 Barcode는 다양한 문자(알파벳, 숫자 또는 기호)를 포함할 수 있으며, 서명 정보, 제목, 주제 또는 짧은 암호화 데이터를 보관하기 위한 유형 및 설정에 따라 길이와 크기가 달라질 수 있습니다.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Barcode 서명의 다양한 옵션을 지정하려면 GroupDocs.Signature for Python via .NET이 [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) 클래스를 제공합니다. 주요 필드는 다음과 같습니다:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

GroupDocs.Signature for Python via .NET API를 사용하여 Barcode 서명으로 문서를 전자 서명하는 단계는 다음과 같습니다:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

이 예제는 Python을 사용하여 Barcode 서명으로 PDF 문서에 서명하는 방법을 보여줍니다:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # 인코딩할 텍스트와 함께 바코드 서명 옵션을 생성합니다
        options = BarcodeSignOptions("John Smith")

        # 바코드 유형을 설정합니다
        options.encode_type = BarcodeTypes.CODE128

        # 바코드 위치와 크기를 설정합니다
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # 문서에 서명하고 결과를 저장합니다
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

바코드 서명을 추가 옵션으로 더 맞춤 설정할 수 있습니다: 정렬 및 여백, 바 색상, 인코딩된 텍스트의 위치, 내부 여백, 배경, 테두리 및 투명도:

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 텍스트와 바코드 유형을 생성자에 전달합니다
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # 바코드를 페이지 오른쪽 하단에 배치합니다
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 바 색상, 바 아래의 인코딩된 텍스트, 테두리 내부 공간
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # 배경, 테두리 및 투명도
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature은 다양한 바코드 유형을 지원합니다. 각 유형은 고유한 문자 집합과 길이를 허용하므로 해당 유형에 맞는 텍스트를 선택하십시오. 이 예제는 한 번의 호출로 서로 다른 유형의 네 개 바코드로 문서에 서명합니다:

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # 바코드당 하나의 서명 옵션 객체를 사용하며, 아래에 차례로 배치합니다
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
이 가이드는 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net)를 사용하여 문서에 바코드 기반 서명을 추가하는 방법을 보여줍니다. 다양한 바코드 유형 및 맞춤 옵션을 지원하는 바코드 서명의 생성, 구성 및 적용에 대해 다룹니다. 추가 탐색을 위해 문서 정보 및 고급 서명 기술에 관한 관련 가이드를 참조하십시오.

## More Resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

바코드를 생성하거나 바코드로 파일에 무료로 서명하려면, [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode) 온라인 앱을 사용할 수 있습니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 다른 온라인 앱을 사용할 수 있습니다.
