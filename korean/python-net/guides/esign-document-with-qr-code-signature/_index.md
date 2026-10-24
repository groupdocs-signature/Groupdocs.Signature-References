---
title: "QR 코드 서명으로 문서 전자 서명"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 문서는 .NET API를 통해 Python용 GroupDocs.Signature를 사용하여 문서 페이지에 QR 코드 전자 서명을 적용하는 방법을 설명합니다."
type: docs
url: /ko/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR 코드(또는 Quick Response 코드)는 흰색 배경에 검은색 정사각형이 격자 형태로 배열된 2차원 [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/)의 일종입니다. QR 코드는 스마트폰 카메라나 QR 전용 장치—핸드헬드 스캐너, 휴대용 단말기, 데스크톱 스캐너, 내장 스캐너 등—로 읽을 수 있습니다. 일반적으로 QR 코드는 웹사이트나 애플리케이션, 이메일, 전화번호, 제품 식별자 또는 추적기와 연결되는 데이터를 포함합니다. 따라서 QR 코드의 활용 범위는 일반 마케팅 및 제품 식별에서부터 문서 관리에 이르기까지 다양합니다.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec 코드 | DataMatrix 코드 | GS1 DataMatrix | GS1 QR 코드 | QR |
| --- | --- | --- | --- | --- | --- |
| **애플리케이션** | * 운송 및 티켓팅;<br> * 항공 산업에서 전자 탑승권;<br> * 철도에서 온라인으로 판매되고 고객이 인쇄하거나 모바일 화면에 표시되는 티켓. 코드는 열차 직원이 휴대용 스캐너로 또는 개찰구에서 스캔하여 티켓을 검증합니다.<br> * 의료 - 환자 식별용 손목밴드 및 일회용 약품 라벨 등 | * 라벨 및 편지와 같은 인쇄 매체;<br> * 산업 공학 목적 - 부품 표시 등;<br>  * 식품 산업 - 식품이 잘못 포장·날짜가 지정되는 것을 방지하기 위해; | 사용 분야<br> * 의료;<br> * 정부;<br> * 산업.<br> 항목의 추가 정보를 인코딩합니다, 예를 들어:<br> * 무게;<br> * 유통 기한;<br> * 배치 번호;<br> * 제조 일자;<br> * 기타; | 마케팅에서 패키지에 추가 항목 정보를 인코딩하는 데 사용됩니다 | 자동차 산업 및 모바일 애플리케이션에서 널리 사용됩니다. 많은 양의 데이터 문자와 특정 URL을 인코딩하는 데 유용합니다. |
| **길이** | 3067 영문자와 숫자,<br> 3832 숫자,<br> 1914 바이트 | 2335 영문자와 숫자,<br> 3116 숫자 | 2335 영문자와 숫자,<br> 3116 숫자,<br> 1556 바이트 | 7089 알파벳 숫자,<br> 4296 숫자,<br> 2953 바이트 | 4296 알파벳 숫자,<br> 7089 숫자,<br> 2953 바이트 |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

문서에 QR 코드 전자 서명을 추가할 때, 주요 설정은 인코딩할 텍스트와 [QR 코드 유형](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields)이며, 이는 [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) 클래스를 통해 지정해야 합니다.

QR 코드 서명을 사용하여 문서에 전자 서명하는 단계는 다음과 같습니다:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

아래 코드 스니펫은 Python을 사용하여 QR 코드 서명으로 PDF 문서에 서명하는 방법을 보여줍니다:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # 인코딩할 텍스트와 함께 QR 코드 서명 옵션을 생성합니다
        options = QrCodeSignOptions("John Smith")

        # QR 코드 유형을 설정합니다
        options.encode_type = QrCodeTypes.QR

        # QR 코드 위치와 크기를 설정합니다
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # 문서에 서명하고 결과를 저장합니다
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf)를 클릭하세요.

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

위 표에 있는 다른 QR 코드 유형도 동일한 방식으로 설정되며, 예를 들어 `QrCodeTypes.AZTEC` 또는 `QrCodeTypes.DATA_MATRIX`와 같습니다.

### Advanced QR Code Options

다음 예시는 정렬 및 여백, 모듈 색상, 배경 및 테두리와 같은 추가 사용자 정의를 통해 보다 복잡한 QR 코드 서명을 만드는 방법을 보여줍니다:

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 텍스트와 QR 코드 유형을 생성자에 전달합니다.
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # 페이지 오른쪽 하단에 QR 코드를 배치합니다.
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 모듈 색상, 배경 및 내부에 약간의 여백이 있는 점선 테두리
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf)를 클릭하세요.

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
이 가이드는 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net)를 사용하여 문서에 QR 코드 서명을 추가하는 방법을 보여줍니다. 여기에는 QR 코드 서명을 생성하고, 크기 및 인코딩과 같은 속성을 구성하며, 문서에 적용하는 단계가 포함됩니다. QR 코드 서명은 서명된 문서를 빠르게 검증하는 데 사용할 수 있습니다.

## More Resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

무료로 QR 코드를 생성하거나 QR 코드로 파일에 서명하려면, 온라인 앱인 [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode)를 사용할 수 있습니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 다른 온라인 앱을 사용할 수 있습니다.
