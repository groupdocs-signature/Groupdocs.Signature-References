---
title: "ProcessProgressEventArgs"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Proporciona datos para el evento OnProgress de los procesos de verificación y búsqueda de firmas."
type: docs
weight: 2130
url: /es/net/groupdocs.signature/processprogresseventargs/
---
## ProcessProgressEventArgs class

Proporciona datos para el evento OnProgress de los procesos de firma, verificación y búsqueda.

```csharp
public class ProcessProgressEventArgs : ProcessEventArgs
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ProcessProgressEventArgs](processprogresseventargs)() | El constructor predeterminado. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Cancel](../../groupdocs.signature/processprogresseventargs/cancel) { get; set; } | Indica si el proceso debe cancelarse. |
| [ProcessedSignatures](../../groupdocs.signature/processprogresseventargs/processedsignatures) { get; set; } | Representa la cantidad de firmas procesadas. |
| [Progress](../../groupdocs.signature/processprogresseventargs/progress) { get; set; } | Representa el progreso en porcentajes. El rango de valores es de 0 a 100. |
| [Status](../../groupdocs.signature/processeventargs/status) { get; set; } | Indica el estado actual del proceso. |
| [Ticks](../../groupdocs.signature/processprogresseventargs/ticks) { get; set; } | Representa el tiempo transcurrido en milisegundos desde el evento Start del proceso. |

### Ver también

* class [ProcessEventArgs](../processeventargs)
* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
