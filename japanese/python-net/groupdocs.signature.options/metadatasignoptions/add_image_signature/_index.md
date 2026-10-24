---
title: "add_image_signature メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された引数で新しい ImageMetadataSignature を作成し、コレクションに追加します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

指定された引数で新しい ImageMetadataSignature を作成し、コレクションに追加します。

```python
def add_image_signature(self, id, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| id | `System.UInt16` | Image Metadata Signature 名の一意の識別子です。可能な ID 値については Exif タグ仕様のリファレンスをご参照ください。 |
| value | `Any` | メタデータの値。 |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### 関連項目
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
