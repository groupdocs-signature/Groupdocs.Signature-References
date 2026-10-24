---
title: "SearchResult 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "지정된 문서에서 서명을 검색한 결과를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

지정된 문서에서 서명을 검색한 결과를 나타냅니다.

SearchResult 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | 검색 결과에 대한 반복자를 반환합니다. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Search 메서드에 대해 항상 0인 대상 문서 크기입니다. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | 검색 기준에 의해 검색 프로세스에서 실패한 서명 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) 목록입니다. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | 검색 프로세스의 실행 시간(밀리초)입니다. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | 찾은 서명 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) 목록입니다. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | 원본 문서 크기. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | 찾은 서명 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) 목록입니다. |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | 검색 프로세스에서 반환된 처리된 서명의 총 개수입니다. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
