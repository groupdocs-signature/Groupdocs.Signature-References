---
title: "to_date_time メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名の値を datetime.datetime に変換します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

メタデータ署名の値を `datetime.datetime` に変換します。

メタデータの値を変換できない場合に例外をスローします。元の値が文字列ベースの場合、デフォルトカルチャーは [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) から使用されます。

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

メタデータ署名の値を `datetime` に変換します。

メタデータの値を変換できなかった場合、例外がスローされます。

```python
def to_date_time(self, provider):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | データ変換操作で使用するフォーマット データプロバイダー。 |

**Returns:** datetime: The metadata signature value as a `datetime`.

### 関連項目
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
