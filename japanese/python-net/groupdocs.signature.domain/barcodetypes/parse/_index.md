---
title: "parse メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定されたパースタイプ名に対する BarcodeType インスタンスを返します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/barcodetypes/parse/
is_root: false
weight: 1010
---


## parse {#parsing_type}

指定されたパースタイプ名に対する BarcodeType インスタンスを返します。

バーコード名が不明な場合、例外がスローされます。

```python
def parse(cls, parsing_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parsing_type | `str` | バーコードタイプ名のソース文字列。 |

**Returns:** BarcodeType: BarcodeType instance.

### 関連項目
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
