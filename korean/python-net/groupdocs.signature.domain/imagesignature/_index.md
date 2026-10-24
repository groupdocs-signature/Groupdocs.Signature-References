---
title: "ImageSignature 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 클래스는 이미지 서명 속성을 포함합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

이 클래스는 이미지 서명 속성을 포함합니다.

ImageSignature 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Sign 또는 Search 메서드에서 얻은 고유 서명 식별자를 사용하여 ImageSignature 객체를 초기화합니다. [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/) 클래스. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | ImageSignature 인스턴스를 복제합니다. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | 지정된 서명이 이 인스턴스와 같은지 여부를 결정합니다. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | 서명의 해시 코드를 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | 서명의 바이너리 이미지 데이터이며, [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) 에서 지정한 형식입니다. |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | 서명 이미지의 형식입니다. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | 서명 이미지의 바이트 단위 크기입니다. |
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
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
