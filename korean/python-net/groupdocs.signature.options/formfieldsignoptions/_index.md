---
title: "FormFieldSignOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PDF 문서에 대한 FormField 서명 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

PDF 문서에 대한 FormField 서명 옵션을 나타냅니다.

PDF 파일에서 양식 필드 서명을 생성하거나 업데이트하기 위한 옵션을 제공합니다.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

FormFieldSignOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | PdfFormFieldSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | PdfFormFieldSignOptions 클래스의 새 인스턴스를 FormField 서명으로 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | 문서 페이지에서 서명 영역의 높이(측정 단위: 픽셀, 퍼센트 또는 밀리미터; `MeasureType` SizeMeasureType을 참조). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | 문서 페이지에서 이미지의 수평 정렬. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | 문서 페이지에서 서명 영역의 왼쪽 X 위치(측정 단위: 픽셀, 퍼센트 또는 밀리미터). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Left 및 Top 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | 이미지와 문서 가장자리 사이의 기본 간격(수평 또는 수직 정렬이 설정된 경우 적용됩니다). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | 여백 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | 시계 방향으로 측정된 회전 각도입니다. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | 서명의 FormField. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Width 및 Height 속성의 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | 문서 페이지의 스트레치 모드. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | 문서 페이지에서 서명 영역의 상단 Y 위치를 측정 단위(픽셀, 퍼센트 또는 밀리미터)로 나타냅니다. 위치 측정 유형에 대해서는 `MeasureType`을 참조하십시오. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | 폼 필드 서명의 투명도. 값은 0.0에서 1.0 사이이며 기본값은 0입니다. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | 문서 페이지에서 이미지의 수직 정렬. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | 문서 페이지에서 서명 영역의 너비(측정값(픽셀, 퍼센트 또는 밀리미터); `MeasureType` SizeMeasureType를 참조). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 서명이 모든 문서 페이지에 배치됩니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 추가 서명 외관. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 서명 배경 설정. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 테두리 설정. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 서명 옵션의 문서 유형 (`DocumentType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 서명 확장자. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 서명의 글꼴. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | 서명의 전경색. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)에서 상속됨) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
