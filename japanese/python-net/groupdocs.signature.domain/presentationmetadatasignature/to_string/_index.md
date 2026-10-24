---
title: "to_string メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名を文字列に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/presentationmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

メタデータ署名を文字列に変換します。

ブール プロパティを "True" または "False" に変換します。その他のデータ型については、デフォルトのデータ形式プロバイダーが使用されます。

```python
def to_string(self):
    ...
```

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

**Returns:** str: The metadata signature value as string.

### 関連項目
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
