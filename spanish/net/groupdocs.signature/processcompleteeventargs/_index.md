---
title: "ProcessCompleteEventArgs"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Proporciona datos sobre el evento de finalización de los procesos de verificación de firmas y búsqueda."
type: docs
weight: 2100
url: /es/net/groupdocs.signature/processcompleteeventargs/
---
## ProcessCompleteEventArgs class

Proporciona datos sobre el evento de finalización de los procesos de firma, verificación y búsqueda.

```csharp
public class ProcessCompleteEventArgs : ProcessEventArgs
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [Canceled](../../groupdocs.signature/processcompleteeventargs/canceled) { get; } | Indica si el proceso fue cancelado. |
| [Completed](../../groupdocs.signature/processcompleteeventargs/completed) { get; set; } | Representa la marca de tiempo de la finalización del proceso. |
| [Status](../../groupdocs.signature/processeventargs/status) { get; set; } | Indica el estado actual del proceso. |
| [Ticks](../../groupdocs.signature/processcompleteeventargs/ticks) { get; set; } | Representa el tiempo en milisegundos transcurrido desde el evento de inicio del proceso. |
| [TotalSignatures](../../groupdocs.signature/processcompleteeventargs/totalsignatures) { get; set; } | Representa la cantidad total de firmas procesadas. |

### Ver también

* class [ProcessEventArgs](../processeventargs)
* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
