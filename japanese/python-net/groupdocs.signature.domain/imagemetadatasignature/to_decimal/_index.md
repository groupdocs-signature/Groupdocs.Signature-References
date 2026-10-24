---
title: "to_decimal メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "Decimal に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Decimal に変換します。

メタデータの値を変換できない場合、例外がスローされます。元の値が文字列ベースの場合、[`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) のデフォルトカルチャが使用されます。

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

メタデータ署名の値を decimal に変換します。

メタデータの値を変換できない場合、例外がスローされます。

```python
def to_decimal(self, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** float: The metadata signature value as a decimal.

### 関連項目
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
