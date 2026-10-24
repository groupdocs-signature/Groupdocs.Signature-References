---
title: "QrCodeSignature 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "QR 코드 서명 속성을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

QR 코드 서명 속성을 나타냅니다.

QrCodeSignature 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | 검색 과정 후에 얻은 서명 식별자를 사용하여 QrCodeSignature 객체를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | QR-Code 서명 인스턴스를 복제합니다. |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | 주어진 서명 객체가 이 인스턴스와 같은지 여부를 판단합니다. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | GetHashCode 메서드를 재정의합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | 형식이 [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/)인 QR-code 바이너리 데이터 이미지 내용입니다. |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | QR-code 인코드 유형입니다. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | QR-code 서명 이미지의 형식입니다. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | QR-code의 텍스트입니다. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 서명 생성 날짜입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | 이 서명이 문서에서 삭제되었는지 여부를 나타내는 플래그입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 서명의 높이입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | 이 구성 요소가 서명(`True`)인지 문서 내용(`False`)인지를 나타내는 플래그입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 서명의 왼쪽 위치. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 서명 수정 날짜. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 서명이 발견된 페이지 번호. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 서명의 고유 식별자이며, 업데이트 또는 삭제 작업을 통해 문서에서 서명을 수정하는 데 사용됩니다. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 서명 유형. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 서명의 상단 위치. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 서명의 너비. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
