---
title: "verify 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用给定的 VerifyOptions 数据验证文档签名。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

使用给定的 VerifyOptions 数据验证文档签名。

更多关于使用 GroupDocs.Signature 进行电子签名文档验证的信息：
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| verify_options | `VerifyOptions` | 签名验证选项。 |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### 示例

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

使用提供的验证选项验证文档签名，并根据指定的谓词过滤结果。

了解更多

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| verify_options | `VerifyOptions` | 签名验证选项。 |
| predicate | `Func[BaseSignature, bool]` | 用于确定哪些签名应被验证的过滤谓词。 |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### 示例

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

使用 VerifyOptions 数据列表验证文档签名。

更多关于使用 GroupDocs.Signature 进行电子签名文档验证的信息： [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)。

```python
def verify(self, verify_options_list):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | 签名验证选项集合。`GroupDocs.Signature.Options.VerifyOptionsCollection` 的实例。 |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### 示例

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

使用提供的验证选项验证文档签名，并使用给定的谓词过滤结果。

该方法首先搜索与验证选项匹配的签名，使用谓词对其进行过滤，然后仅验证这些过滤后的签名。

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | 签名验证选项集合。 |
| predicate | `Func[BaseSignature, bool]` | 用于确定哪些签名应被验证的过滤谓词。 |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### 示例

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

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
