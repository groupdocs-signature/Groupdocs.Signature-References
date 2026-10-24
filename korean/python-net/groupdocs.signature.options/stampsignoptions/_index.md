---
title: "StampSignOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "스탬프 서명 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

스탬프 서명 옵션을 나타냅니다.

자세히 보기:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

StampSignOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | StampSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | StampSignOptions 클래스의 새 인스턴스를 정렬 옵션과 함께 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 내부 리소스를 정리합니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Base64 문자열에서 미리 정의된 이미지를 사용하여 새로운 ImageSignOptions 인스턴스를 생성합니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | 스탬프의 배경입니다. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | 서명의 배경 색상 자르기 유형. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | 서명의 배경 이미지 자르기 유형. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | 문서 페이지에서 서명 영역의 높이(측정 단위: 픽셀, 퍼센트 또는 밀리미터). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | 문서 페이지에서 이미지의 수평 정렬. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | 내부 선 목록이 사각형 집합으로 렌더링됩니다. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | 문서 페이지에서 서명 영역의 왼쪽 X 위치(측정 단위: 픽셀, 퍼센트 또는 밀리미터). `MeasureType` `LocationMeasureType`을 참조하십시오. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | 이미지와 문서 가장자리 사이에 기본적으로 지정되는 공간(수평 또는 수직 정렬이 지정된 경우에 작동합니다). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | 여백 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | 외부 선 목록이 동심 원으로 렌더링됩니다. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | 시계 방향 회전 각도. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Width 및 Height 속성의 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | 스탬프 유형. 기본값은 `Round`입니다. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | 문서 페이지에서의 스트레치 모드입니다. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | 문서 페이지에서 서명 영역의 상단 Y 위치(측정 단위: 픽셀, 퍼센트 또는 밀리미터). `MeasureType` `LocationMeasureType`을 참조하십시오. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | 스탬프 서명의 투명도. 값은 0.0에서 1.0 사이이며 기본값은 0입니다. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | 문서 페이지에서 스탬프의 수직 정렬. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | 문서 페이지에서 서명 영역의 너비(측정 값: 픽셀, 퍼센트 또는 밀리미터). 측정 단위는 `MeasureType` SizeMeasureType에 의해 정의됩니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 서명이 모든 문서 페이지에 배치됩니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 추가 서명 외관. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | 이미지 서명의 테두리 설정입니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 서명 옵션의 문서 유형 (`DocumentType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 서명 확장자. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 암호화 작업에 사용할 해시 알고리즘. PDF 파일의 디지털 서명에만 지원됩니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | 서명 이미지의 파일 경로이며, `image_stream`이 지정되지 않은 경우에만 사용됩니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | 서명 이미지 스트림입니다. 지정된 경우 항상 ImageFilePath 대신 사용됩니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 서명을 위한 문서 페이지 번호. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 서명할 페이지를 지정하는 옵션. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | 문서에 이미지를 배치할 영역의 사각형입니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | 도형 위치는 도형이 문서 레이아웃에 표시될 위치를 정의합니다. Word 문서에서만 사용할 수 있습니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 서명 유형 (`SignatureType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | 텍스트 서명의 Z-순서 위치로, 겹치는 서명의 표시 순서를 결정합니다. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # 필요에 따라 추가 스탬프 옵션을 구성하십시오
    signature.sign(options)
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
