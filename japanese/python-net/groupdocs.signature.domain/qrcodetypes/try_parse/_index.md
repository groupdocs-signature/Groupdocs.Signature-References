---
title: "try_parse メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された解析タイプ名に一致する QRCode タイプを返します。名前が不明な場合は None を返します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

指定された解析タイプ名に一致する QRCode タイプを返します。名前が不明な場合は None を返します。

```python
def try_parse(cls, parsing_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parsing_type | `str` | QRCode 型名のソース文字列です。 |

**Returns:** QrCodeTypes or None: QRCode type instance, or None when the name is not recognized.

### 関連項目
* class [`QrCodeTypes`](/signature/python-net/groupdocs.signature.domain/qrcodetypes/)
