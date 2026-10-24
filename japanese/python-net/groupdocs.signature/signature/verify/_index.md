---
title: "verify メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された VerifyOptions データでドキュメントの署名を検証します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

指定された VerifyOptions データでドキュメントの署名を検証します。

GroupDocs.Signature を使用した電子署名ドキュメントの検証に関する詳細: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| verify_options | `VerifyOptions` | 署名検証オプションです。 |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options-predicate}

提供された検証オプションを使用してドキュメントの署名を検証し、指定された述語に基づいて結果をフィルタリングします。

詳細を見る

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| verify_options | `VerifyOptions` | 署名検証オプションです。 |
| predicate | `Func[BaseSignature, bool]` | どの署名を検証すべきかを決定するフィルタ述語。 |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options, lambda s: True)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list}

VerifyOptions データのリストでドキュメントの署名を検証します。

GroupDocs.Signature を使用した電子署名ドキュメントの検証に関する詳細: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | 署名検証オプションコレクションです。`GroupDocs.Signature.Options.VerifyOptionsCollection` のインスタンス。 |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list-predicate}

提供された検証オプションを使用して文書の署名を検証し、指定された述語で結果をフィルタリングします。

このメソッドはまず、検証オプションに一致する署名を検索し、述語を使用してフィルタリングし、フィルタされた署名のみを検証します。

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | 署名検証オプションコレクションです。 |
| predicate | `Func[BaseSignature, bool]` | どの署名を検証すべきかを決定するフィルタ述語。 |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify([options], lambda s: s.text == "John Smith")
        print(f"Document is signed by John Smith: {result[0].is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
