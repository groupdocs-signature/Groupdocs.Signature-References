---
title: "log_level 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "确定传递给 SignatureSettings.Logger 的消息类型的日志级别标志。"
type: docs
url: /zh/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

决定哪些类型的消息会传递给 [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) 的日志级别标志。

该值是一组可以组合的 `LogLevel` 标志，例如 `LogLevel.Error | LogLevel.Warning`。`LogLevel.None` 不记录任何内容。默认是 `LogLevel.All`：错误、警告和跟踪。

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### 另见
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
