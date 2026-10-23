---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用作为流提供的文档初始化新的 Signature 实例。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

使用作为流提供的文档初始化新的 Signature 实例。

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 文档内容流。 |

## __init__ {#document-load_options}

使用文档流和加载选项初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。

了解更多

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 文档内容流。 |
| load_options | `LoadOptions` | 文档加载选项。 |

## __init__ {#document-settings}

使用通过流提供的文档和可选的 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) 初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。

了解更多：

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 文档内容流。 |
| settings | `SignatureSettings` | 签名设置。 |

## __init__ {#document-load_options-settings}

使用文档流、加载选项和签名设置初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 文档内容流。 |
| load_options | `LoadOptions` | 文档加载选项。 |
| settings | `SignatureSettings` | 签名设置。 |

## __init__ {#file_path}

使用文件路径提供的文档初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 绝对或相对文件路径。 |

### 示例

```python
from groupdocs.signature import Signature

# 打开文档以进行签名、搜索或验证
with Signature("sample.pdf") as signature:
    # 使用签名对象
    pass
```

## __init__ {#file_path-load_options}

使用文件路径提供的文档和加载选项初始化新的 Signature 实例。

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 绝对或相对文件路径。 |
| load_options | `LoadOptions` | 文档加载选项。 |

### 示例

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # 执行签名、搜索或验证操作
    pass
```

## __init__ {#file_path-settings}

使用文件路径提供的文档和可选的 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) 初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 绝对或相对文件路径。 |
| settings | `SignatureSettings` | 签名设置。 |

### 示例

```python
from groupdocs.signature import Signature

# 打开 PDF 文档进行签名或验证
with Signature("sample.pdf") as signature:
    # 在此使用签名实例（例如，sign、verify、search）
    pass
```

## __init__ {#file_path-load_options-settings}

使用文件路径提供的文档、加载选项和签名设置初始化新的 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 实例。

了解更多：
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 绝对或相对文件路径。 |
| load_options | `LoadOptions` | 文档加载选项。 |
| settings | `SignatureSettings` | 签名设置。 |

### 示例

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # 执行签名、验证或搜索操作
    pass
```

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
