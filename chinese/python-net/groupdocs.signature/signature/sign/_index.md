---
title: "sign 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用 SignOptions 对文档进行签名并将结果保存到流中。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并将结果保存到流中。

```python
def sign(self, document, sign_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 输出文档流。 |
| sign_options | `SignOptions` | 签名选项。 |

**Returns:** SignResult: Instance containing list of newly created signatures.

备注：
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### 示例

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

使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到流中。

了解更多
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 输出文档流。 |
| sign_options | `SignOptions` | 签名选项。 |
| save_options | `SaveOptions` | 保存选项。 |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

使用一组 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并将结果保存到流中。

了解更多

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 输出文档流。 |
| sign_options_list | `List[SignOptions]` | 签名选项列表。 |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

使用一组 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到流中。

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 输出文档流。 |
| sign_options_list | `List[SignOptions]` | 签名选项列表。 |
| save_options | `SaveOptions` | 保存选项。 |

**Returns:** SignResult: Instance containing the list of newly created signatures.

备注：
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 签名并将结果保存到新文件；源文件保持不变
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

使用 SignOptions 对文档进行签名，并将结果保存到指定的文件路径。

了解更多

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 输出文件路径。 |
| sign_options | `SignOptions` | 签名选项。 |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### 示例

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

使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到指定的文件路径。

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 输出文件路径。 |
| sign_options | `SignOptions` | 签名选项。 |
| save_options | `SaveOptions` | 保存选项。 |

**Returns:** SignResult: Instance with list of newly created signatures.

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # 打开文档；with-block 在结束时会释放文件。
    with Signature("sample.pdf") as signature:
        # 文本签名位于第一页左边缘和上边缘各 100 像素处
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 签名并将结果保存到新文件；源文件保持不变
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

使用 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 集合对文档进行签名，并将结果保存到指定的文件路径。

了解更多：
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 输出文件路径。 |
| sign_options_list | `List[SignOptions]` | 签名选项列表。 |

**Returns:** SignResult: Instance with list of newly created signatures.

### 示例

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

使用一组 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 对文档进行签名，并使用预定义的 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) 将结果保存到指定的文件路径。

了解更多：
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 输出文件路径。 |
| sign_options_list | `List[SignOptions]` | 签名选项列表。 |
| save_options | `SaveOptions` | 保存选项。 |

**Returns:** SignResult: Instance with list of newly created signatures.

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
