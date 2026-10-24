---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "証明書ファイルで DigitalVBA クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

証明書ファイルで DigitalVBA クラスの新しいインスタンスを初期化します。

```python
def __init__(self, certificate_file_path, password):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_file_path | `str` | デジタル証明書のファイルパスです。 |
| password | `str` | デジタル証明書のパスワードです。 |

### 例

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# 証明書ファイルとパスワードを使用して DigitalVBA 拡張機能を作成する
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

証明書ストリームで DigitalVBA クラスの新しいインスタンスを初期化します。

```python
def __init__(self, certificate_stream, password):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | デジタル証明書を含む io.RawIOBase。 |
| password | `str` | デジタル証明書用の str パスワード。 |

### 関連項目
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
