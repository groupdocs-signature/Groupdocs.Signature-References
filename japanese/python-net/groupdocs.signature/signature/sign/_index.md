---
title: "sign メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "SignOptions を使用してドキュメントに署名し、結果をストリームに保存します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) を使用してドキュメントに署名し、結果をストリームに保存します。

```python
def sign(self, document, sign_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | 出力ドキュメントストリームです。 |
| sign_options | `SignOptions` | 署名オプションです。 |

**Returns:** SignResult: Instance containing list of newly created signatures.

備考:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#document-sign_options-save_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) を使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果をストリームに保存します。

詳細を見る
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | 出力ドキュメントストリームです。 |
| sign_options | `SignOptions` | 署名オプションです。 |
| save_options | `SaveOptions` | 保存オプションです。 |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、結果をストリームに保存します。

詳細を見る

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | 出力ドキュメントストリームです。 |
| sign_options_list | `List[SignOptions]` | 署名オプションの一覧です。 |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果をストリームに保存します。

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | 出力ドキュメントストリームです。 |
| sign_options_list | `List[SignOptions]` | 署名オプションの一覧です。 |
| save_options | `SaveOptions` | 保存オプションです。 |

**Returns:** SignResult: Instance containing the list of newly created signatures.

備考:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 署名して結果を新しいファイルに保存します；元のファイルは変更されません。
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

SignOptions を使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。

詳細を見る

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 出力ファイルパスです。 |
| sign_options | `SignOptions` | 署名オプションです。 |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options-save_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) を使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果を指定されたファイルパスに保存します。

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 出力ファイルパスです。 |
| sign_options | `SignOptions` | 署名オプションです。 |
| save_options | `SaveOptions` | 保存オプションです。 |

**Returns:** SignResult: Instance with list of newly created signatures.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # ドキュメントを開きます；with ブロックは終了時にファイルを解放します。
    with Signature("sample.pdf") as signature:
        # 最初のページの左端と上端から 100 ピクセル離れた位置にテキスト署名を配置します。
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 署名して結果を新しいファイルに保存します；元のファイルは変更されません。
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。

詳しくは以下をご覧ください:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 出力ファイルパスです。 |
| sign_options_list | `List[SignOptions]` | 署名オプションの一覧です。 |

**Returns:** SignResult: Instance with list of newly created signatures.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    options.left = 100
    options.top = 100
    result = signature.sign("signed_sample.pdf", options)
    print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list-save_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果を指定されたファイルパスに保存します。

詳しくは以下をご覧ください:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 出力ファイルパスです。 |
| sign_options_list | `List[SignOptions]` | 署名オプションの一覧です。 |
| save_options | `SaveOptions` | 保存オプションです。 |

**Returns:** SignResult: Instance with list of newly created signatures.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
