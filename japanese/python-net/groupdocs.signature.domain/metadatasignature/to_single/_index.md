---
title: "to_single メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名の値を float に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

メタデータ署名の値を float に変換します。

メタデータの値を変換できない場合に例外をスローします。元の値が文字列ベースの場合、デフォルトカルチャーは [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) から使用されます。

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

float に変換します。

```python
def to_single(self, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** float: The Metadata Signature value as float.

### 関連項目
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
