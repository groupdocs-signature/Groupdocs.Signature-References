---
title: "Error"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación."
type: docs
weight: 20
url: /es/net/groupdocs.signature.logging/filelogger/error/
---
## FileLogger.Error method

Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

```csharp
public void Error(string message, Exception ex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | String | El mensaje de error. |
| ex | Excepción | La excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzada cuando *message* es nulo. |
| ArgumentNullException | Lanzada cuando *ex* es nulo. |

### Ver también

* class [FileLogger](../../filelogger)
* namespace [GroupDocs.Signature.Logging](../../../groupdocs.signature.logging)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
