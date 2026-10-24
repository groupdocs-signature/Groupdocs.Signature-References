---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ストリームとして提供されたドキュメントで新しい Signature インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

ストリームとして提供されたドキュメントで新しい Signature インスタンスを初期化します。

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントのコンテンツストリームです。 |

## __init__ {#document-load_options}

ドキュメントストリームとロードオプションで新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。

詳細を見る

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントのコンテンツストリームです。 |
| load_options | `LoadOptions` | ドキュメントのロードオプションです。 |

## __init__ {#document-settings}

ストリームで提供されたドキュメントとオプションの [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) で新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。

詳しくは以下をご覧ください:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントのコンテンツストリームです。 |
| settings | `SignatureSettings` | 署名設定です。 |

## __init__ {#document-load_options-settings}

ドキュメントストリーム、ロードオプション、署名設定を使用して新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントのコンテンツストリームです。 |
| load_options | `LoadOptions` | ドキュメントのロードオプションです。 |
| settings | `SignatureSettings` | 署名設定です。 |

## __init__ {#file_path}

ファイルパスで提供されたドキュメントで新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 絶対パスまたは相対パス。 |

### 例

```python
from groupdocs.signature import Signature

# 署名、検索、または検証のためにドキュメントを開く
with Signature("sample.pdf") as signature:
    # 署名オブジェクトを操作する
    pass
```

## __init__ {#file_path-load_options}

ファイルパスで提供されたドキュメントとロードオプションで新しい Signature インスタンスを初期化します。

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 絶対パスまたは相対パス。 |
| load_options | `LoadOptions` | ドキュメントのロードオプションです。 |

### 例

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # 署名、検索、または検証操作を実行する
    pass
```

## __init__ {#file_path-settings}

ファイルパスで提供されたドキュメントとオプションの [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) で新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 絶対パスまたは相対パス。 |
| settings | `SignatureSettings` | 署名設定です。 |

### 例

```python
from groupdocs.signature import Signature

# 署名または検証のために PDF ドキュメントを開く
with Signature("sample.pdf") as signature:
    # ここで署名インスタンスを使用する（例: sign、verify、search）
    pass
```

## __init__ {#file_path-load_options-settings}

ファイルパスで提供されたドキュメント、ロードオプション、署名設定を使用して新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。

詳しくは以下をご覧ください:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 絶対パスまたは相対パス。 |
| load_options | `LoadOptions` | ドキュメントのロードオプションです。 |
| settings | `SignatureSettings` | 署名設定です。 |

### 例

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # 署名、検証、または検索操作を実行する
    pass
```

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
