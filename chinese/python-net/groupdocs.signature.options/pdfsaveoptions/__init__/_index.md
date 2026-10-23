---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 PdfSaveOptions 的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 PdfSaveOptions 的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

使用指定的输出文件格式初始化 PdfSaveOptions 的新实例。

```python
def __init__(self, file_format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | 输出文件类型 `PdfSaveFileFormat`。 |

## __init__ {#overwrite_existing_file}

使用覆盖标志初始化 PdfSaveOptions 的新实例。

```python
def __init__(self, overwrite_existing_file):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| overwrite_existing_file | `bool` | 指示是否使用相同文件覆盖已签名文件的标志。 |

## __init__ {#file_format-overwrite_existing_file}

使用指定的输出文件格式和覆盖标志初始化 PdfSaveOptions 的新实例。

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | 输出文件类型。 |
| overwrite_existing_file | `bool` | 指示是否使用相同文件覆盖已签名文件的标志。 |

### 示例

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# 创建 PDF 格式的保存选项并允许覆盖现有文件
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### 另见
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
