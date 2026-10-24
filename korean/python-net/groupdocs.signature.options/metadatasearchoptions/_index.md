---
title: "MetadataSearchOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "메타데이터 서명에 대한 검색 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

메타데이터 서명에 대한 검색 옵션을 나타냅니다.

문서에서 메타데이터 서명을 검색하도록 구성하는 옵션을 제공합니다.

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

MetadataSearchOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | 기본값으로 MetadataSearchOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | 이 옵션 컬렉션 내의 모든 메타데이터 서명을 복호화하는 데 사용되는 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) 구현입니다. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | 문서 통계 및 정보와 같은 내장 문서 속성이 검색 결과에 포함되는지 여부를 나타내는 플래그입니다. |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | 검색 및 일치시킬 메타데이터 서명 이름입니다. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | 검색에 사용되는 메타데이터 이름 일치 유형입니다. `name` 속성이 설정된 경우에만 적용됩니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 각 문서 페이지에서 검색할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 검색을 위한 문서 페이지 번호(옵션). ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 서명 검색을 위한 페이지를 지정하는 옵션입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 문서 레이아웃에서 도형 위치를 반환할지 여부를 나타내는 플래그입니다. Word 문서에서만 사용할 수 있습니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` 로 표시된 서명만 반환하는 플래그입니다. 기본값은 `False`이며, 이는 지정된 기준에 맞는 모든 서명이 반환됨을 의미합니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
