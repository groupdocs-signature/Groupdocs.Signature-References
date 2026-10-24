---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で DigitalVerifyOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で DigitalVerifyOptions インスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

指定されたデジタル証明書ファイルパスで DigitalVerifyOptions インスタンスを初期化します。

```python
def __init__(self, certificate_file_path):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_file_path | `str` | デジタル証明書へのファイルパスです。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

指定された証明書ストリームで DigitalVerifyOptions インスタンスを初期化します。

```python
def __init__(self, certificate_stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 証明書のストリームです。 |

### 関連項目
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
