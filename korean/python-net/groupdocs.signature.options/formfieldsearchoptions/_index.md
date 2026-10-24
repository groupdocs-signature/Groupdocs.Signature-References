---
title: "FormFieldSearchOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "양식 필드 서명에 대한 검색 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

양식 필드 서명에 대한 검색 옵션을 나타냅니다.

자세히 보기:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

FormFieldSearchOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | 기본값으로 FormFieldSearchOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | 검색 중에 양식 필드 서명 이름과 일치시키는 데 사용되는 정규식 패턴입니다. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | 검색할 양식 필드 서명의 유형입니다. 기본값은 None입니다. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | 검색할 양식 필드 서명의 값입니다. 기본값은 None입니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 각 문서 페이지에서 검색할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 검색을 위한 문서 페이지 번호(옵션). ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 서명 검색을 위한 페이지를 지정하는 옵션입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 문서 레이아웃에서 도형 위치를 반환할지 여부를 나타내는 플래그입니다. Word 문서에서만 사용할 수 있습니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` 로 표시된 서명만 반환하는 플래그입니다. 기본값은 `False`이며, 이는 지정된 기준에 맞는 모든 서명이 반환됨을 의미합니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # "ApprovedBy"라는 이름의 텍스트 필드만 반환합니다
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
