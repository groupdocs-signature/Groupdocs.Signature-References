---
title: "FileLogger"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Escribe mensajes de registro en el archivo."
type: docs
weight: 1340
url: /es/net/groupdocs.signature.logging/filelogger/
---
## FileLogger class

Escribe mensajes de registro en el archivo.

```csharp
public class FileLogger : ILogger
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileLogger](filelogger)(string) | Crear registrador en archivo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Error](../../groupdocs.signature.logging/filelogger/error)(string, Exception) | Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación. |
| [Trace](../../groupdocs.signature.logging/filelogger/trace)(string) | Escribe un mensaje de rastreo en la consola. Los mensajes de registro de rastreo proporcionan información generalmente útil sobre el flujo de la aplicación. |
| [Warning](../../groupdocs.signature.logging/filelogger/warning)(string) | Escribe un mensaje de advertencia en la consola; Los mensajes de registro de advertencia proporcionan información sobre el evento inesperado y recuperable en el flujo de la aplicación. |

### Ver también

* interface [ILogger](../ilogger)
* namespace [GroupDocs.Signature.Logging](../../groupdocs.signature.logging)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
