---
title: "Event 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示标准二维码事件详情。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

表示标准二维码事件详情。

Event 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | 使用默认值初始化 Event 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | 比较此 Event 与另一个 Event 是否相等。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | 返回 Event 的哈希码。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | 事件的描述。 |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | 事件结束日期和时间。 |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | 事件地点。 |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | 事件开始日期和时间。 |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | 事件标题。 |

### 示例

```python
from datetime import datetime
from groupdocs.signature.domain.extensions import Event

event_qr = Event()
event_qr.title = "Meeting"
event_qr.description = "Productivity issues"
event_qr.location = "room 408"
event_qr.start_date = datetime(2022, 6, 19, 15, 30, 0)
event_qr.end_date = datetime(2022, 6, 19, 17, 0, 0)
```

### 另见
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
