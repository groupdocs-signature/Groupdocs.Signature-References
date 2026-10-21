---
title: "ProcessProgressEventHandler"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa un delegado de método que manejará procesos en eventos de progreso para la verificación de firmas y búsqueda."
type: docs
weight: 2140
url: /es/net/groupdocs.signature/processprogresseventhandler/
---
## ProcessProgressEventHandler delegate

Representa un delegado de método que manejará los procesos en los eventos de progreso para la firma, verificación y búsqueda.

```csharp
public delegate void ProcessProgressEventHandler(Signature signature, 
    ProcessProgressEventArgs args);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firma | Firma | Objeto de firma |
| args | ProcessProgressEventArgs | Argumentos [`ProcessProgressEventArgs`](../processprogresseventargs) que especifican propiedades del evento de progreso. |

### Ver también

* class [Signature](../signature)
* class [ProcessProgressEventArgs](../processprogresseventargs)
* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
