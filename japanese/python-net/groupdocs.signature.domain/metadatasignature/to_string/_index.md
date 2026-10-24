---
title: "to_string メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名を文字列に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

メタデータ署名を文字列に変換します。

ブール型プロパティを "True" または "False" に変換します。他のデータ型については、デフォルトのデータフォーマットプロバイダーが使用されます。

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

指定された形式を使用してメタデータ署名を文字列に変換します。

ブール型プロパティを "True" または "False" に変換します。デフォルトカルチャのプロパティ情報は SignatureSettings のプロパティ [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) から使用されます。

```python
def to_string(self, format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| format | `str` | データ形式文字列。 |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

指定された形式で文字列に変換します。

ブールプロパティを "True" または "False" に変換します。

```python
def to_string(self, format, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| format | `str` | データ形式文字列。 |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** The metadata signature value as a string.

### 関連項目
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
