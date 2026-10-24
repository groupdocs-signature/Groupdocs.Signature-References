---
title: "QrCodeSignOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "QR-Code 서명 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

QR-Code 서명 옵션을 나타냅니다.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

QrCodeSignOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | QRCodeSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | 지정된 텍스트로 QR 코드 서명 옵션 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | 텍스트와 함께 QrCodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | 결과 QR 코드 이미지에서 텍스트 정렬, 기본값은 None입니다. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | QR-Code 콘텐츠로 직렬화할 사용자 정의 객체. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | QR 코드 서명 텍스트 또는 데이터를 인코딩 및 디코딩하는 데 사용되는 데이터 암호화 구현. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | QR-Code 유형. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | QR 코드 바의 전경색; 이 속성을 사용하면 검증 문제가 발생할 수 있으므로 신중히 사용하십시오. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | 문서 페이지에서 서명 영역의 높이(측정 단위: 픽셀, 퍼센트 또는 밀리미터; `MeasureType` SizeMeasureType을 참조). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | 문서 페이지에서 QR 코드의 수평 정렬. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | QR 코드 요소와 결과 이미지 경계 사이의 공간. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | 문서 페이지에서 서명 영역의 왼쪽 X 위치(측정 단위: 픽셀, 퍼센트 또는 밀리미터). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | QR-code 로고 이미지 파일 이름. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | QR-code 로고 이미지 스트림. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | 이미지와 문서 가장자리 사이에 기본적으로 지정되는 공간(수평 또는 수직 정렬이 지정된 경우에 작동). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | 여백 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | 문서 페이지에 배치된 서명의 QR-Code 이미지 콘텐츠를 가져오는 플래그. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | `return_content` 속성이 활성화된 경우 QR‑Code 서명의 반환된 이미지 콘텐츠 파일 형식. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | 시계 방향으로 회전 각도(도). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Width 및 Height 속성의 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | 문서 페이지에서의 스트레치 모드입니다. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | 문서 페이지에서 서명 영역의 상단 Y 위치(측정 단위: 픽셀, 퍼센트 또는 밀리미터). 단위는 `MeasureType` 유형의 `LocationMeasureType` 속성에 의해 정의됩니다. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | QR 코드 서명의 투명도. 값 범위는 0.0에서 1.0이며, 기본값은 0입니다. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | 문서 페이지에서 이미지의 수직 정렬. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | 문서 페이지에서 서명 영역의 너비(측정 값: `MeasureType`에 정의된 픽셀, 퍼센트 또는 밀리미터). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 서명이 모든 문서 페이지에 배치됩니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 추가 서명 외관. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 서명 배경 설정. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 테두리 설정. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 서명 옵션의 문서 유형 (`DocumentType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 서명 확장자. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 서명의 글꼴. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | 텍스트 서명을 배치할 텍스트 양식 필드의 제목. `signature_implementation`가 `TextSignatureImplementation.FORM_FIELD`로 설정된 경우에만 사용할 수 있습니다. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | 텍스트 서명을 배치할 양식 필드 유형. 이 속성은 `signature_implementation`가 `TextSignatureImplementation.FORM_FIELD`(즉, TextToFormField)로 설정된 경우에만 적용됩니다. 기본값은 `FormTextFieldType.ALL_TEXT_TYPES`입니다. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 암호화 작업에 사용할 해시 알고리즘. PDF 파일의 디지털 서명에만 지원됩니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | 네이티브 속성. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 서명을 위한 문서 페이지 번호. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 서명할 페이지를 지정하는 옵션. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | 도형 위치는 도형이 문서 레이아웃에 표시될 위치를 정의합니다. Word 문서에서만 사용할 수 있습니다. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | 텍스트를 넣을 도형 유형. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | 서명의 고유 ID로, 검증 옵션에서 사용할 수 있으며 PDF 문서에서만 지원됩니다. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | 텍스트 서명 구현 유형. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 서명 유형 (`SignatureType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | 서명의 텍스트. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | 서명 내부 텍스트의 가로 정렬이며, 이미지 및 주석 서명 구현에서만 지원됩니다(`TextSignatureImplementation` SignatureImplementation 속성 참조). ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | 서명 내부 텍스트의 수직 정렬. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | 텍스트 서명의 Z-순서 위치로, 겹치는 서명의 표시 순서를 결정합니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### 예시

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

        signature.sign("signed.pdf", options)
```

### Guides
`QrCodeSignOptions`를 사용하는 작업 가이드:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
