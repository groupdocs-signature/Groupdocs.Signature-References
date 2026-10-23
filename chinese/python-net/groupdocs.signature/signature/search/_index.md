---
title: "search 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用 SearchOptions 列表在文档中搜索签名。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

使用一组 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) 在文档中搜索签名。

了解更多

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | 搜索选项集合。 |

**Returns:** SearchResult: Instance containing the list of found signatures.

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

使用提供的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。

了解更多：
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | 一个由 `SearchOptions` 实例组成的列表，用于定义搜索签名的条件。 |
| predicate | `Func[BaseSignature, bool]` | 对已找到的签名列表应用的过滤谓词。 |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 在每页上查找文本签名
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

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

通过 `SignatureType` 值在文档中搜索指定的签名类型。

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | 要查找的一种或多种签名类型。 |

**Returns:** SearchResult: Instance containing the list of found signatures.

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 在每页上查找文本签名
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

使用所有可用的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – 一个接受 `BaseSignature` 并返回 `True`（保留签名）或 `False`（丢弃签名）的函数。 |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # 搜索文本签名并使用自定义谓词进行过滤
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
