---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された識別子と値で画像メタデータ署名を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

指定された識別子と値で画像メタデータ署名を初期化します。

```python
def __init__(self, id, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| id | `System.UInt16` | Image Metadata 署名の一意の識別子です。可能な id 値については、EXIF タグ仕様のリファレンスをご参照ください。 |
| value | `Any` | メタデータの値です。 |

### 例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### 関連項目
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
