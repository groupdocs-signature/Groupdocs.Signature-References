---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用零值初始化 Padding 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

使用零值初始化 Padding 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature.domain import Padding

# 创建具有默认（零）值的填充对象
default_padding = Padding()
```

## __init__ {#all}

使用提供的填充尺寸为所有边缘初始化 Padding 类的新实例。

```python
def __init__(self, all):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| all | `int` | 用于所有边缘填充的度量单位数量。 |

### 示例

```python
# 所有侧面统一 5 单位的填充
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

使用提供的填充尺寸初始化 Padding 类的新实例。

```python
def __init__(self, left, right, top, bottom):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| left | `int` | 左侧填充大小。 |
| right | `int` | 右侧填充大小。 |
| top | `int` | 顶部填充大小。 |
| bottom | `int` | 底部填充大小。 |

### 示例

```python
from groupdocs.signature.domain import Padding

# 创建具有右侧和底部偏移的填充
margin = Padding(right=40, bottom=60)
```

### 另见
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
