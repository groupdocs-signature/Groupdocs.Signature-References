---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "DigitalSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

DigitalSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

証明書ファイルを使用して新しい DigitalSignOptions インスタンスを初期化します。

```python
def __init__(self, certificate_file_path):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_file_path | `str` | デジタル証明書のファイルパスです。 |

### 例

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

証明書ストリームを使用して新しい DigitalSignOptions インスタンスを初期化します。

```python
def __init__(self, certificate_stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | デジタル証明書ストリームです。 |

### 例

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

証明書ファイルと外観画像ファイルを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_file_path | `str` | デジタル証明書のファイルパスです。 |
| image_file_path | `str` | 署名外観画像のファイルパスです。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # コンストラクタに証明書と外観画像を渡します
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

証明書ファイルと外観画像ストリームを使用して DigitalSignOptions の新しいインスタンスを初期化します。

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_file_path | `str` | デジタル証明書のファイルパスです。 |
| appearence_image_stream | `io.RawIOBase` | 署名外観画像のストリームです。 |

### 例

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

証明書ストリームと外観画像ファイルを使用して DigitalSignOptions の新しいインスタンスを初期化します。

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase。デジタル証明書ストリームです。 |
| image_file_path | `str` | str。署名外観画像のファイルパスです。 |

## __init__ {#certificate_stream-appearence_image_stream}

証明書ストリームと外観画像ストリームを使用して新しい DigitalSignOptions インスタンスを初期化します。

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | デジタル証明書ストリームです。 |
| appearence_image_stream | `io.RawIOBase` | 署名外観画像のストリームです。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # ストリームから証明書と外観画像をロードします
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### 関連項目
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
