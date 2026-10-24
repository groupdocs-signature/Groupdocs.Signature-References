---
title: "search 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "SearchOptions 목록을 사용하여 문서에서 서명을 검색합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

문서에서 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) 목록을 사용하여 서명을 검색합니다.

자세히 알아보기

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | 검색 옵션 컬렉션. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

제공된 검색 옵션을 사용하여 문서에서 서명을 검색하고 지정된 술어에 따라 결과를 필터링합니다.

자세히 보기:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | `SearchOptions` 인스턴스 목록으로, 서명을 검색하기 위한 기준을 정의합니다. |
| predicate | `Func[BaseSignature, bool]` | 찾은 서명 목록에 적용할 필터 프레디케이트. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 각 페이지에서 텍스트 서명을 찾습니다.
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#search_options}

```python
def search(self, search_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

`SignatureType` 값으로 문서에서 지정된 서명 유형을 검색합니다.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | 찾을 서명의 하나 또는 여러 유형. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 각 페이지에서 텍스트 서명을 찾습니다.
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

사용 가능한 모든 검색 옵션을 사용하여 문서에서 서명을 검색하고 지정된 술어에 따라 결과를 필터링합니다.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – `BaseSignature`를 받아 서명을 유지하려면 `True`를, 버리려면 `False`를 반환하는 함수. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # 텍스트 서명을 검색하고 사용자 정의 프레디케이트로 필터링합니다.
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
