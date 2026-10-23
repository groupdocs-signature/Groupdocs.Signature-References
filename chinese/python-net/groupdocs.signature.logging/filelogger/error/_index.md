---
title: "error 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将错误信息写入控制台。"
type: docs
url: /zh/python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

将错误信息写入控制台。

Error 日志消息提供有关应用程序流程中不可恢复事件的信息。

```python
def error(self, message, ex):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| message | `str` | 错误消息。 |
| ex | `Exception` | 异常。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `ex` 为 None。 |

### 另见
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
