---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で ImageSignOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で ImageSignOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature.options import ImageSignOptions

# 画像ファイルパスを使用して画像署名オプションを作成する
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

画像ファイルで ImageSignOptions を初期化します。

```python
def __init__(self, image_file_path):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| image_file_path | `str` | 画像ファイルのパス。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # ここで追加オプションを構成します。例: 位置、サイズなど。
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

画像ストリームで新しい ImageSignOptions インスタンスを初期化します。

```python
def __init__(self, image_stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | 画像ストリーム。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### 関連項目
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
