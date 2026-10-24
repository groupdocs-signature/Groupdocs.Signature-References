---
title: "ImageSignOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이미지 서명 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

이미지 서명 옵션을 나타냅니다.

자세히 보기:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

ImageSignOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | ImageSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | 이미지 파일로 ImageSignOptions를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | 이미지 스트림으로 새 ImageSignOptions 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 내부 리소스를 정리합니다. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Base64 문자열에서 미리 정의된 이미지를 사용하여 새 ImageSignOptions 인스턴스를 생성합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | 이미지 서명의 테두리 설정입니다. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | 문서 페이지에서 서명의 높이를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 지정합니다(`MeasureType` SizeMeasureType 참조). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | 문서 페이지에서 서명의 가로 정렬입니다. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | `image_stream`이 지정되지 않은 경우에만 사용되는 서명 이미지 파일 경로입니다. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | 서명 이미지 스트림입니다. 지정된 경우 항상 ImageFilePath 대신 사용됩니다. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | 문서 페이지에서 서명의 왼쪽 X 위치를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 지정합니다. 가로 정렬이 지정되지 않은 경우에 작동합니다. 위치 측정 유형은 `MeasureType`을 참조하십시오. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | 서명과 문서 가장자리 사이의 간격입니다. 가로 또는 세로 정렬이 지정된 경우에만 작동합니다. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | 문서에 이미지를 배치할 영역의 사각형입니다. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | 문서 페이지에서 서명의 회전 각도(시계 방향)입니다. |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | 도형 위치는 도형이 문서 레이아웃에 표시될 위치를 정의합니다. Word 문서에서만 사용할 수 있습니다. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Width 및 Height 속성의 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | 문서 페이지에서의 스트레치 모드입니다. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | `MeasureType` LocationMeasureType에 정의된 대로 문서 페이지에서 서명의 상단 Y 위치를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 지정합니다. 세로 정렬이 지정되지 않은 경우에 작동합니다. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | 서명 투명도는 0.0(불투명)에서 1.0(투명)까지이며, 기본값은 0(불투명)입니다. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | 문서 페이지에서 서명의 수직 정렬. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | 문서 페이지에서 서명의 너비를 측정 값(픽셀, 퍼센트 또는 밀리미터 `MeasureType` 크기 측정 유형)으로 지정합니다. |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # 이미지 파일로 이미지 서명 옵션을 생성합니다
        options = ImageSignOptions("signature.jpg")
        # 서명의 위치와 크기를 설정합니다
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
`ImageSignOptions`를 사용하는 작업 가이드:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
