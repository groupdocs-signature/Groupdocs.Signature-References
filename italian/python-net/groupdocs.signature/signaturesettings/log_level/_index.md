---
title: "proprietà log_level"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "I flag del livello di log che determinano quali tipi di messaggi vengono passati a SignatureSettings.Logger."
type: docs
url: /it/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

I flag di livello di log che determinano quali tipi di messaggi vengono passati a [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

Il valore è un insieme di flag `LogLevel` che possono essere combinati, ad esempio `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` non registra nulla. Il valore predefinito è `LogLevel.All`: errori, avvisi e tracce.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Vedi anche
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
