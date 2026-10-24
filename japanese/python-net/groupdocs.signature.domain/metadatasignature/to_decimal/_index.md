---
title: "to_decimal メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名の値を Decimal に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

メタデータ署名の値を Decimal に変換します。

メタデータの値を変換できない場合に例外をスローします。元の値が文字列ベースの場合、デフォルトカルチャーのプロパティ情報は [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) から使用されます。

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

メタデータ署名の値を Decimal に変換します。

```python
def to_decimal(self, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** The metadata signature value as Decimal.

### 関連項目
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
