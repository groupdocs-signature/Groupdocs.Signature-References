---
title: "data_encryption プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "このオプションコレクション内のすべてのメタデータ署名を暗号化するために使用される IDataEncryption の実装です。"
type: docs
url: /ja/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

[`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) の実装は、このオプションコレクション内のすべてのメタデータ署名を暗号化するために使用されます。

設定されている場合、すべての追加された署名はデフォルトでこの暗号化を使用します。ただし、独自の DataEncryption が割り当てられている場合は除きます。

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### 関連項目
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
