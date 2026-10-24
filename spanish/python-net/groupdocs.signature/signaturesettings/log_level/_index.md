---
title: "propiedad log_level"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Los indicadores de nivel de registro que determinan qué tipos de mensajes se envían a SignatureSettings.Logger."
type: docs
url: /es/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Las banderas de nivel de registro que determinan qué tipos de mensajes se envían a [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

El valor es un conjunto de banderas `LogLevel` que pueden combinarse, por ejemplo `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` no registra nada. El valor predeterminado es `LogLevel.All`: errores, advertencias y trazas.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Ver también
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
