---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で Event インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で Event インスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

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

### 関連項目
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
