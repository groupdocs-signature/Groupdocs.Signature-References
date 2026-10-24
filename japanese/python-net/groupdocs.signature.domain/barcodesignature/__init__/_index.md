---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "検索プロセス後に取得した署名識別子で BarcodeSignature オブジェクトを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/barcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

検索プロセス後に取得した署名識別子で BarcodeSignature オブジェクトを初期化します。識別子は、ドキュメントの署名情報レイヤーからこの署名の追加プロパティを取得するために使用されます。

```python
def __init__(self, signature_id):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_id | `str` | `Signature` の `Sign` または `Search` メソッドで取得されたユニークな署名識別子。 |

### 関連項目
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature/)
