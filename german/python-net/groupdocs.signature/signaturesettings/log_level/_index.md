---
title: "log_level Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Log-Level-Flags, die bestimmen, welche Arten von Nachrichten an SignatureSettings.Logger übergeben werden."
type: docs
url: /de/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Die Log‑Level‑Flags, die bestimmen, welche Arten von Nachrichten an [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) weitergeleitet werden.

Der Wert ist eine Menge von `LogLevel`-Flags, die kombiniert werden können, zum Beispiel `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` protokolliert nichts. Der Standard ist `LogLevel.All`: Fehler, Warnungen und Traces.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Siehe auch
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
