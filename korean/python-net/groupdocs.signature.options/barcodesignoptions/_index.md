---
title: "BarcodeSignOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "바코드 서명 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

바코드 서명 옵션을 나타냅니다.

자세히 알아보기

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

BarcodeSignOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | BarcodeSignOptions 클래스를 기본값으로 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | 텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | 텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | 결과 바코드 이미지에서 텍스트 정렬입니다. 기본값은 None입니다. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | 바코드 유형입니다. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | 바코드 바의 전경색입니다; 사용하면 검증 문제가 발생할 수 있으므로 신중히 사용하십시오. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | 문서 페이지에서 서명 영역의 높이이며 측정 단위(픽셀, 퍼센트 또는 밀리미터)로 지정합니다. 크기 측정 유형은 `MeasureType`을 참조하십시오. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | 문서 페이지에서 이미지의 수평 정렬. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | 바코드 요소와 결과 이미지 경계 사이의 간격입니다. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | 문서 페이지에서 서명 영역의 왼쪽 X 위치이며 측정 단위(픽셀, 퍼센트 또는 밀리미터)로 표현됩니다. `MeasureType`을 참조하십시오. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | 이미지와 문서 가장자리 사이에 기본적으로 지정되는 공간(수평 또는 수직 정렬이 설정된 경우 적용됩니다). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | 여백 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | 문서 페이지에 배치된 서명의 바코드 이미지 내용을 가져올지 여부를 나타내는 플래그입니다. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | `return_content` 속성이 활성화된 경우 Barcode 서명의 반환된 이미지 내용의 파일 유형입니다. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | 시계 방향 회전 각도. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Width 및 Height 속성의 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | 문서 페이지에서의 스트레치 모드입니다. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | 문서 페이지에서 서명 영역의 상단 Y 위치이며 측정 단위(픽셀, 퍼센트 또는 밀리미터)로 지정합니다. `MeasureType` LocationMeasureType을 참조하십시오. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | 바코드 서명의 투명도이며 0.0(완전 불투명)에서 1.0(완전 투명)까지 범위입니다; 기본값은 0입니다. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | 문서 페이지에서 바코드 이미지의 수직 정렬. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | `MeasureType`에 정의된 측정 값(픽셀, 퍼센트 또는 밀리미터)으로 문서 페이지의 서명 영역 너비. |
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
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
`BarcodeSignOptions`를 사용하는 작업 가이드:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
