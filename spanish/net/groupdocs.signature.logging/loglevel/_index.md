---
title: LogLevel
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Especifica los tipos de nivel de registro disponibles. Esta enumeración se puede utilizar como indicadores para establecer varios valores posibles como bits habilitados Ejemplo LogLevel.Error x7C LogLevel.Warning o LogLevel.Error x7C LogLevel.Trace
type: docs
weight: 1170
url: /es/net/groupdocs.signature.logging/loglevel/
---
## LogLevel enumeration

Especifica los tipos de nivel de registro disponibles. Esta enumeración se puede utilizar como indicadores para establecer varios valores posibles como bits habilitados Ejemplo: LogLevel.Error &#x7C; LogLevel.Warning o LogLevel.Error &#x7C; LogLevel.Trace

```csharp
[Flags]
public enum LogLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Sin limitación de registro, toda la información se registrará desde el seguimiento, advirtiendo a los errores |
| Error | `1` | Sin limitación de registro, toda la información se registrará desde el seguimiento, advirtiendo a los errores |
| Warning | `2` | Igual que el nivel Todos, todos los mensajes, incluido el nivel de seguimiento, se registrarán |
| Trace | `4` | El nivel de registro para incluir mensajes del nivel de advertencia a error |
| All | `7` | Todos los eventos de nivel de registro (Error, Advertencia, Seguimiento) se incluirán en logging |

### Ver también

* espacio de nombres [GroupDocs.Signature.Logging](../../groupdocs.signature.logging)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
