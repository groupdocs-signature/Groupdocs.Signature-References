---
title: "to_date_time メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名の値を datetime に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

メタデータ署名の値を datetime に変換します。

メタデータの値を変換できない場合、例外がスローされます。元の値が文字列ベースの場合、変換には [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) のデフォルトカルチャが使用されます。

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

メタデータ署名の値を datetime に変換します。

```python
def to_date_time(self, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

メタデータの値を変換できなかった場合、例外がスローされます。

### 関連項目
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
