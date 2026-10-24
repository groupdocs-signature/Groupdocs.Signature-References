---
title: "свойство log_level"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаги уровня журналирования, определяющие, какие типы сообщений передаются в SignatureSettings.Logger."
type: docs
url: /ru/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Флаги уровней логирования, определяющие, какие типы сообщений передаются в [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

Значение представляет собой набор флагов `LogLevel`, которые можно комбинировать, например `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` ничего не записывает. По умолчанию используется `LogLevel.All`: ошибки, предупреждения и трассировки.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### См. также
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
