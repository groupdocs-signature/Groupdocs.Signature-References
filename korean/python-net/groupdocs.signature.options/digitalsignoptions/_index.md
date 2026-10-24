---
title: "DigitalSignOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "디지털 서명 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

디지털 서명 옵션을 나타냅니다.

자세히 알아보기

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

DigitalSignOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | DigitalSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | 인증서 파일을 사용하여 새로운 DigitalSignOptions 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | 인증서 스트림을 사용하여 새로운 DigitalSignOptions 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | 인증서 파일과 외관 이미지 파일을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | 인증서 파일과 외관 이미지 스트림을 사용하여 DigitalSignOptions의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | 인증서 스트림과 외관 이미지 파일을 사용하여 DigitalSignOptions의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | 인증서 스트림과 외관 이미지 스트림을 사용하여 새로운 DigitalSignOptions 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 내부 리소스를 정리합니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Base64 문자열에서 미리 정의된 이미지를 사용하여 새로운 ImageSignOptions 인스턴스를 생성합니다. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | 유효 기간이 만료된 인증서로 서명하도록 허용하는 플래그입니다. 기본값은 False이며, 만료된 인증서로 서명하면 `GroupDocsSignatureException`이 발생하고 문서는 서명되지 않습니다. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | 유효 기간이 아직 시작되지 않은 인증서로 서명하도록 허용하는 플래그입니다. 기본값은 False이며, 이러한 인증서로 서명하면 `GroupDocsSignatureException`이 발생하고 문서는 서명되지 않습니다. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | 디지털 인증서 파일 경로입니다. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | 디지털 인증서 스트림입니다. 이 속성이 지정되면 항상 CertificateFilePath 대신 사용됩니다. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | 서명 연락처입니다. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | 문서를 서명하는 데 사용되는 사용자 정의 해시 서명 함수로, 사용자가 자체 디지털 서명 로직을 구현할 수 있게 합니다. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | 문서 페이지에서 서명 영역의 높이이며 측정 단위(픽셀, 퍼센트 또는 밀리미터)로 표시됩니다(`MeasureType` 참조). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | 문서 페이지에서 이미지의 수평 정렬. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | 문서 페이지에서 서명 영역의 왼쪽 X 위치이며, 측정 단위(픽셀, 퍼센트 또는 `MeasureType.location_measure_type`에 정의된 밀리미터)로 표시됩니다. |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | 서명 위치입니다. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)입니다. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | 이미지와 문서 가장자리 사이에 기본적으로 지정되는 간격(수평 또는 수직 정렬이 지정된 경우에 적용됩니다). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | 여백 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | 디지털 인증서의 비밀번호입니다. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | 서명의 이유입니다. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | 시계 방향 회전 각도. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | 문서에 대한 디지털 서명 속성입니다. PDF 서명의 경우, 고급 속성을 [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/) 인스턴스를 사용하여 설정할 수 있습니다. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Width 및 Height 속성의 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | 문서 페이지에서의 스트레치 모드입니다. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | 문서 페이지에서 서명 영역의 위쪽 Y 위치이며, 측정 단위(픽셀, 퍼센트 또는 밀리미터)로 표시됩니다(`MeasureType` `LocationMeasureType` 참조). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | 디지털 서명의 투명도이며, 0.0에서 1.0 사이입니다. 기본값은 0입니다. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | LTV(장기 검증) 검증 플래그. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | 문서 페이지에서 이미지의 수직 정렬. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | 서명의 가시성. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | 문서 페이지에서 서명 영역의 너비를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 지정합니다. 측정 단위는 `MeasureType`을 통해 SizeMeasureType 속성에서 정의됩니다. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | XAdES 유형입니다. 기본값은 None이며 (XAdES가 비활성화됨). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 생성자에 인증서와 외관 이미지를 전달합니다.
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # 페이지에 서명을 표시하고, 지정된 위치와 크기로 나타냅니다.
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # 서명에 저장된 정보
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
`DigitalSignOptions`를 사용하는 작업 가이드:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
