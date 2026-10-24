---
title: "to_single メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "float に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

float に変換します。

Metadata の値を変換できない場合、例外がスローされます。元の値が文字列ベースの場合、デフォルトのカルチャ プロパティ情報は [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) から使用されます。

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

メタデータ署名の値を float に変換します。

メタデータの値を変換できない場合、例外がスローされます。

```python
def to_single(self, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** float: The metadata signature value as a float.

### 関連項目
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
