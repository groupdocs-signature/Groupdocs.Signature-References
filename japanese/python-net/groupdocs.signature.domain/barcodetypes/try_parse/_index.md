---
title: "try_parse メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定されたパースタイプ名に一致する Barcode タイプを返します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

指定されたパースタイプ名に一致する Barcode タイプを返します。

名前が不明な場合、メソッドは例外をスローする代わりに None を返します。

```python
def try_parse(cls, parsing_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parsing_type | `str` | バーコードタイプ名のソース文字列。 |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### 関連項目
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
