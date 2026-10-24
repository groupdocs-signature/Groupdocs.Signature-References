---
title: "log_level-eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De log level-vlaggen die bepalen welke soorten berichten worden doorgestuurd naar SignatureSettings.Logger."
type: docs
url: /nl/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

De logniveau‑vlaggen die bepalen welke soorten berichten worden doorgegeven aan [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

De waarde is een set van `LogLevel`‑vlaggen die gecombineerd kunnen worden, bijvoorbeeld `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` logt niets. Standaard is `LogLevel.All`: fouten, waarschuwingen en traces.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Zie ook
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
