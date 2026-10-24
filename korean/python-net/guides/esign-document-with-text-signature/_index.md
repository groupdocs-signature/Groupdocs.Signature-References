---
title: "텍스트 서명을 사용한 전자 서명 문서"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 문서는 GroupDocs.Signature for Python via .NET API를 사용하여 텍스트 서명으로 문서에 서명하는 방법을 설명합니다. Python에서 프로그래밍 방식으로 PDF에 디지털 서명을 추가하는 방법을 배울 수 있습니다."
type: docs
url: /ko/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

**Text** 전자 서명은 문서 유형에 따라 네이티브 방식으로 문서에 추가되는 임의의 텍스트입니다. GroupDocs.Signature는 텍스트 서명 기능을 제공하며 글꼴 이름, 크기, 색상부터 정렬, 테두리, 그림자 효과 등에 이르는 다양한 텍스트 설정을 사용자 정의할 수 있습니다. 텍스트 서명이 다음과 같이 표시될 수 있습니다:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Python을 사용하여 프로그래밍 방식으로 PDF에 텍스트 서명을 추가해 봅시다.

프로그래밍 방식으로 텍스트 서명을 조작하려면 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net)가 [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) 클래스를 제공하며 전체 워크플로는 다음과 같이 간단합니다:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

이 예제는 Python을 사용하여 문서에 텍스트 서명을 추가하는 방법을 보여줍니다:

{{< tabs \"sign_with_text_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # 텍스트 서명 옵션 만들기
        options = TextSignOptions("John Smith")

        # 서명의 위치와 크기를 설정합니다
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # 텍스트 색상 및 글꼴 설정
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # 문서에 서명하고 결과를 저장합니다
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은(는) 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_text.pdf\" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

텍스트 서명을 추가 옵션으로 더 사용자 지정할 수 있습니다: 정렬 및 여백, 글꼴 스타일, 배경, 테두리, 회전 및 투명도. 정렬이 설정되면 `left` 또는 `top` 좌표를 대체하고, `margin`은 페이지 가장자리에서 서명을 오프셋합니다.

{{< tabs \"sign_with_text_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # 페이지 오른쪽 하단에 서명을 배치하십시오.
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 글꼴 스타일 및 텍스트 색상
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # 배경, 테두리, 회전 및 투명도
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # 텍스트를 이미지로 렌더링하여 PDF 페이지에 테두리도 그립니다.
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은(는) 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_text_advanced.pdf\" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
이 가이드는 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net)를 사용하여 문서에 텍스트 기반 서명을 추가하는 방법을 설명합니다. 글꼴, 색상, 크기 및 위치와 같은 텍스트 속성을 구성하고, �스트 서명을 문서에 적용하는 내용을 다룹니다. 서명이 추가된 문서는 텍스트 서명이 포함된 상태로 저장됩니다.

## More Resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 온라인 앱을 사용할 수 있습니다.
