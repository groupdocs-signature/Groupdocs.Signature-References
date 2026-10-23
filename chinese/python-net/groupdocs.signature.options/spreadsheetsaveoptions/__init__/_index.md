---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 SpreadsheetSaveOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/spreadsheetsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 SpreadsheetSaveOptions 类的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

使用预定义的输出文件格式初始化 SpreadsheetSaveOptions 的新实例。

```python
def __init__(self, file_format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_format | `SpreadsheetSaveFileFormat` | 指定输出文件格式。 |

## __init__ {#file_format-overwrite_existing_file}

使用指定的输出文件格式和覆盖标志初始化 SpreadsheetSaveOptions 的新实例。

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_format | `SpreadsheetSaveFileFormat` | 指定输出文件格式。 |
| overwrite_existing_file | `bool` | 指示是否使用相同文件覆盖已签名文件的标志。 |

### 另见
* class [`SpreadsheetSaveOptions`](/signature/python-net/groupdocs.signature.options/spreadsheetsaveoptions/)
