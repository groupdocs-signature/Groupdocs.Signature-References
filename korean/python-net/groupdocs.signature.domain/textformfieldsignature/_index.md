---
title: "TextFormFieldSignature 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PDF 문서에 대한 텍스트 입력 양식 필드 서명 속성을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

PDF 문서에 대한 텍스트 입력 양식 필드 서명 속성을 나타냅니다.

TextFormFieldSignature 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | 미리 정의된 이름으로 PdfTextFormFieldSignature을 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | 미리 정의된 이름으로 PdfTextFormFieldSignature을 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | FormField Signature 인스턴스를 복제합니다. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | 유형 및 속성 값을 기반으로 이 서명을 다른 서명과 동등성 비교합니다. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | GetHashCode 메서드를 재정의합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | 폼 필드 입력의 텍스트. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 서명 생성 날짜입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | 이 서명이 문서에서 삭제되었는지 여부를 나타내는 플래그입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 서명의 높이입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | 이 구성 요소가 서명(`True`)인지 문서 내용(`False`)인지를 나타내는 플래그입니다. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에서 상속됨) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 서명의 왼쪽 위치. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 서명 수정 날짜. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | 고유한 양식 필드 이름입니다. ([`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 서명이 발견된 페이지 번호. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 서명의 고유 식별자이며, 업데이트 또는 삭제 작업을 통해 문서에서 서명을 수정하는 데 사용됩니다. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 서명 유형. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 서명의 상단 위치. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | 양식 필드 유형입니다. ([`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)에서 상속됨) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | 양식 필드 데이터 객체입니다. ([`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)에서 상속됨) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 서명의 너비. (상속됨: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # 값 "Value1"을 가진 "FieldText"라는 텍스트 폼 필드를 생성합니다.
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # 해당 항목에 대한 양식 필드 옵션을 생성합니다
        options = FormFieldSignOptions(text_field)

        # 양식 필드 위치와 크기를 설정합니다
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # 문서에 서명하고 결과를 저장합니다
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
