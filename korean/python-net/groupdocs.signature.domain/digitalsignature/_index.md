---
title: "DigitalSignature 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 클래스는 디지털 서명 속성을 포함합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

이 클래스는 디지털 서명 속성을 포함합니다.

DigitalSignature 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | 기본 매개변수로 디지털 서명을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | 알려진 서명 식별자를 사용하여 디지털 서명을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | 지정된 X509 저장소의 첫 번째 인증서를 사용하여 DigitalSignature를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | 지정된 X509 저장소와 인증서 인덱스를 기반으로 DigitalSignature를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | 지정된 인증서를 사용하여 디지털 서명을 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | 바코드 서명 인스턴스를 복제합니다. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | 이 서명을 다른 서명과 비교하여 동일한지 확인합니다. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | 디지털 서명의 해시 코드를 반환합니다. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | 시스템의 모든 X509 인증서 저장소에서 디지털 서명을 로드합니다. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | 인증서 저장소에서 디지털 서명을 로드합니다. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | 인증서 저장소에서 디지털 서명을 로드합니다. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | 특정 위치에 배치된 디지털 인증서 저장소에서 디지털 서명을 로드합니다. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | 특정 위치에 배치된 디지털 인증서 저장소에서 디지털 서명을 로드합니다. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | 디지털 서명과 연결된 X509 인증서. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | 인증서의 사용자 지정 저장소 이름. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | 인증서의 저장소 위치. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | 인증서의 저장소 이름. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | 서명 목적 주석. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | 디지털 서명이 유효하며 문서가 변조되지 않았습니다. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | 문서가 서명된 시간. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | 인증서의 지문. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | XAdES 유형 ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
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
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
