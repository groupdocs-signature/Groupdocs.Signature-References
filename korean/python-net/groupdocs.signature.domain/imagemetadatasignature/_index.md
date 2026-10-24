---
title: "ImageMetadataSignature 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이미지 메타데이터 서명을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

이미지 메타데이터 서명을 나타냅니다.

이미지 문서에 대한 메타데이터 서명은 EXIF와 같은 이미지 메타데이터 표준을 기반으로 하는 전자 서명입니다. 각 서명은 숫자 식별자(0‑65535)로 식별되며 텍스트, 날짜/시간, 정수, 부동소수점 등 다양한 유형의 값을 저장합니다.

ImageMetadataSignature 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | 지정된 식별자와 값으로 이미지 메타데이터 서명을 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | Metadata Signature 인스턴스를 복제합니다. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | 주어진 값으로 ImageMetadataSignature 인스턴스를 복제합니다. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | 지정된 서명 객체가 이 인스턴스와 같은지 여부를 결정합니다. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | 서명의 해시 코드를 반환합니다. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | 메타데이터 서명 값을 불리언으로 변환합니다. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | 메타데이터 서명 값을 `datetime.datetime` 로 변환합니다. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | 메타데이터 서명 값을 `datetime` 로 변환합니다. |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Decimal 로 변환합니다. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | 메타데이터 서명 값을 decimal 로 변환합니다. |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | float 로 변환합니다. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | 메타데이터 서명 값을 float으로 변환합니다. |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | 메타데이터 서명 값을 정수로 변환합니다. |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | long 로 변환합니다. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | float으로 변환합니다. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | 메타데이터 서명 값을 float으로 변환합니다. |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | 메타데이터 서명 값을 문자열로 변환합니다. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | 지정된 형식을 사용하여 메타데이터 서명 값을 문자열로 변환합니다. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | 지정된 형식으로 문자열로 변환합니다. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)에서 상속됨) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | 표준 이미지 메타데이터 서명의 설명입니다. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | 이미지 메타데이터 서명의 식별자입니다. 사전 정의된 Id 값을 가진 표준 서명을 포함하는 `GroupDocs.Signature.Domain.ImageMetadataSignatures` 클래스를 참조하십시오. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | 메타데이터 값의 크기입니다. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 서명 생성 날짜입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) 구현은 서명 값 속성을 인코딩하고 디코딩하는 데 사용됩니다. ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)에서 상속됨) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | 이 서명이 문서에서 삭제되었는지 여부를 나타내는 플래그입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 서명의 높이입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | 이 구성 요소가 서명(`True`)인지 문서 내용(`False`)인지를 나타내는 플래그입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 서명의 왼쪽 위치. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 서명 수정 날짜. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | 고유 메타데이터 이름. (상속됨: [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 서명이 발견된 페이지 번호. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 서명의 고유 식별자이며, 업데이트 또는 삭제 작업을 통해 문서에서 서명을 수정하는 데 사용됩니다. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 서명 유형. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 서명의 상단 위치. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | 메타데이터 값 유형. (상속됨: [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | 메타데이터 객체. (상속됨: [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 서명의 너비. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### 예시

```python
from datetime import datetime

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
