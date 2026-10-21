---
title: "ProcessCompleteEventHandler"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa un delegado de método que manejará procesos en eventos de finalización para la verificación de firmas y búsqueda."
type: docs
weight: 2110
url: /es/net/groupdocs.signature/processcompleteeventhandler/
---
## ProcessCompleteEventHandler delegate

Representa un delegado de método que manejará los procesos en los eventos de finalización para la firma, verificación y búsqueda.

```csharp
public delegate void ProcessCompleteEventHandler(Signature signature, 
    ProcessCompleteEventArgs args);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firma | Firma | Objeto de firma |
| args | ProcessCompleteEventArgs | Argumentos [`ProcessCompleteEventArgs`](../processcompleteeventargs) que especifican propiedades del evento completado. |

### Ver también

* class [Signature](../signature)
* class [ProcessCompleteEventArgs](../processcompleteeventargs)
* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
