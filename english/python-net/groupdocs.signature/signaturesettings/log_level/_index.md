---
title: log_level property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The log level flags that determine which kinds of messages are passed to SignatureSettings.Logger."
type: docs
url: /python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

The log level flags that determine which kinds of messages are passed to [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

The value is a set of `LogLevel` flags that can be combined, for example `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` logs nothing. The default is `LogLevel.All`: errors, warnings and traces.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### See Also
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
