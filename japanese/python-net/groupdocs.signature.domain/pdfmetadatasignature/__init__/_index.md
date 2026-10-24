---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "事前定義された名前と空の値で PDF メタデータ署名を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

事前定義された名前と空の値で PDF メタデータ署名を初期化します。

```python
def __init__(self, name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | PDF メタデータ署名名。 |

## __init__ {#name-value}

事前定義された値で PDF メタデータ署名を初期化します。

```python
def __init__(self, name, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | メタデータ署名オブジェクトの名前。 |
| value | `Any` | メタデータ署名の値。 |

### 例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

事前定義された値で PDF メタデータ署名を初期化します。

```python
def __init__(self, name, value, tag):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | メタデータ署名オブジェクトの名前。 |
| value | `Any` | メタデータ署名の値。 |
| tag | `str` | メタデータ署名のプレフィックスタグ。 |

### 例

```python
from groupdocs.signature.domain import PdfMetadataSignature

# PDF の作成者用メタデータ署名を作成する
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# 作成日用メタデータ署名を作成する
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# 数値識別子用メタデータ署名を作成する
id_sig = PdfMetadataSignature("DocumentId", 123456)

# 浮動小数点値用メタデータ署名を作成する
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### 関連項目
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
