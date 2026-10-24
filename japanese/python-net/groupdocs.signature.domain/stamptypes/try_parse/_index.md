---
title: "try_parse メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定されたパース型名に対するスタンプタイプを返します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/stamptypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

指定されたパース タイプ名に対するスタンプ タイプを返します。スタンプ名が不明な場合、例外はスローされず、メソッドは None を返します。

```python
def try_parse(cls, parsing_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parsing_type | `str` | スタンプ型名のソース文字列です。 |

**Returns:** StampType: StampType instance.

### 関連項目
* class [`StampTypes`](/signature/python-net/groupdocs.signature.domain/stamptypes/)
