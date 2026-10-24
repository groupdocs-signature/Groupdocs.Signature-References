---
title: "data_encryption プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "このオプションコレクション内のすべてのメタデータ署名を復号化するために使用される IDataEncryption の実装。"
type: docs
url: /ja/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

このオプションコレクション内のすべてのメタデータ署名を復号化するために使用される [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) の実装です。

設定されている場合、独自の DataEncryption が割り当てられていない限り、見つかったすべての署名はデフォルトでこの暗号化を使用します。

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
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
