---
title: error method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Writes an error message to the console."
type: docs
url: /python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Writes an error message to the console.

Error log messages provide information about unrecoverable events in application flow.

```python
def error(self, message, ex):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| message | `str` | The error message. |
| ex | `Exception` | The exception. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `ex` is None. |

### See Also
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
