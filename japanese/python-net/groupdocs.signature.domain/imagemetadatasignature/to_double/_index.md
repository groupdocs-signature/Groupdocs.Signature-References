---
title: "to_double メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "float に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

float に変換します。

メタデータの値を変換できない場合に例外をスローします。元の値が文字列ベースの場合、デフォルトカルチャーは [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) から使用されます。

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

メタデータ署名の値を float に変換します。

指定された形式データプロバイダーを使用して変換を実行します。

```python
def to_double(self, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** float: The metadata signature value as a float.

### 関連項目
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
