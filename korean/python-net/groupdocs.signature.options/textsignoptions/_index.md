---
title: "TextSignOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "텍스트 서명 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

텍스트 서명 옵션을 나타냅니다.

자세히 알아보기

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

TextSignOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | 기본값으로 TextSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | 텍스트와 함께 TextSignOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 서명 배경 설정. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 테두리 설정. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 서명의 글꼴. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | 서명의 전경 색상. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | 텍스트 서명을 배치할 텍스트 양식 필드의 제목입니다. `signature_implementation`이 `TextSignatureImplementation.FORM_FIELD`로 설정된 경우에만 사용할 수 있습니다. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | 텍스트 서명을 배치할 양식 필드 유형입니다. 이 속성은 `signature_implementation`이 `TextSignatureImplementation.FORM_FIELD`(예: TextToFormField)로 설정된 경우에만 적용됩니다. 기본값은 `FormTextFieldType.ALL_TEXT_TYPES`입니다. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | 문서 페이지에서 서명의 높이(측정값: 픽셀, 퍼센트 또는 밀리미터)입니다. 단위는 `SizeMeasureType` 속성에 의해 결정됩니다. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | 문서 페이지에서 서명의 가로 정렬입니다. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | 문서 페이지에서 서명의 왼쪽 X 위치(측정값: `MeasureType` LocationMeasureType 속성에 정의된 픽셀, 퍼센트 또는 밀리미터). 수평 정렬이 지정되지 않은 경우에 작동합니다. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | `left` 및 `top` 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | 서명과 문서 가장자리 사이의 공간입니다. 수평 또는 수직 정렬이 지정된 경우에만 적용됩니다. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | 네이티브 속성. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | 문서 페이지에서 서명의 회전 각도(시계 방향)입니다. |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | 도형 위치는 도형이 문서 레이아웃에 표시될 위치를 정의합니다. Word 문서에서만 사용할 수 있습니다. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | 텍스트를 넣을 도형 유형. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | 서명의 고유 ID로, 검증 옵션에서 사용할 수 있으며 PDF 문서에만 지원됩니다. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | 텍스트 서명 구현 유형. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Width 및 Height 속성의 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | 문서 페이지의 스트레치 모드. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | 서명의 텍스트. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | 서명 내부 텍스트의 수평 정렬이며, 이미지 및 주석 서명 구현에만 지원됩니다(`TextSignatureImplementation` SignatureImplementation 속성을 참조). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | 서명 내부 텍스트의 세로 정렬. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | 문서 페이지에서 서명의 상단 Y 위치이며, 측정 단위(픽셀, 퍼센트 또는 밀리미터)로 표시됩니다. |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | 서명 투명도이며, 0.0(불투명)에서 1.0(투명) 사이의 부동 소수점 값입니다. 기본값은 0.0(불투명)입니다. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | 문서 페이지에서 서명의 수직 정렬. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | 문서 페이지에서 서명의 너비(측정값: 픽셀, 퍼센트 또는 밀리미터; `MeasureType` `SizeMeasureType` 속성을 참조). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 서명이 모든 문서 페이지에 배치됩니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 추가 서명 외관. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 서명 옵션의 문서 유형 (`DocumentType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 서명 확장자. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 암호화 작업에 사용할 해시 알고리즘. PDF 파일의 디지털 서명에만 지원됩니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 서명을 위한 문서 페이지 번호. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 서명할 페이지를 지정하는 옵션. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 서명 유형 (`SignatureType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | 텍스트 서명의 Z-순서 위치로, 겹치는 서명의 표시 순서를 결정합니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
`TextSignOptions`를 사용하는 작업 가이드:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
