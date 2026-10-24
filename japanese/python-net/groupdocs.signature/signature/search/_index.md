---
title: "search メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "SearchOptions のリストを使用して、ドキュメント内の署名を検索します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

リストの [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) を使用してドキュメント内の署名を検索します。

詳細を見る

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | 検索オプションのコレクション。 |

**Returns:** SearchResult: Instance containing the list of found signatures.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

提供された検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。

詳しくは以下をご覧ください:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | 署名検索の基準を定義する `SearchOptions` インスタンスのリスト。 |
| predicate | `Func[BaseSignature, bool]` | 見つかった署名のリストに適用するフィルタ述語。 |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 各ページでテキスト署名を検索します
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

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

`SignatureType` の値でドキュメント内の指定された署名タイプを検索します。

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | 検索対象となる1つまたは複数の署名タイプ。 |

**Returns:** SearchResult: Instance containing the list of found signatures.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 各ページでテキスト署名を検索します
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

利用可能なすべての検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – `BaseSignature` を受け取り、署名を保持する場合は `True`、破棄する場合は `False` を返す関数。 |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # テキスト署名を検索し、カスタム述語でフィルタリングする
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
