---
title: "SearchResult クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定されたドキュメント内で署名を検索した結果を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

指定されたドキュメント内で署名を検索した結果を表します。

SearchResult 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | 検索結果のイテレータを返します。 |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Search メソッドでは常に 0 になる、宛先ドキュメントのサイズです。 |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | 検索条件により検索プロセスで失敗した署名のリスト [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)です。 |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | 検索プロセスの実行時間（ミリ秒）です。 |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | 見つかった署名のリスト [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)です。 |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | ソースドキュメントのサイズ。 |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | 見つかった署名のリスト（[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)）です。 |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | 検索プロセスで返された処理された署名の総数です。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
