---
title: "IResult"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Interfaz común para el resultado del proceso de firma."
type: docs
weight: 700
url: /es/net/groupdocs.signature.domain/iresult/
---
## IResult interface

Interfaz común para el resultado del proceso de firma.

```csharp
public interface IResult
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/iresult/destindocumentsize) { get; } | Devuelve el tamaño del documento de destino |
| [Failed](../../groupdocs.signature.domain/iresult/failed) { get; } | Lista de firmas que no fueron procesadas [`BaseSignature`](../basesignature). |
| [ProcessingTime](../../groupdocs.signature.domain/iresult/processingtime) { get; } | Devuelve el tiempo de ejecución del proceso en milisegundos |
| [SourceDocumentSize](../../groupdocs.signature.domain/iresult/sourcedocumentsize) { get; } | Devuelve el tamaño del documento de origen |
| [Succeeded](../../groupdocs.signature.domain/iresult/succeeded) { get; } | Lista de firmas procesadas exitosamente [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/iresult/totalsignatures) { get; } | Devuelve el total de firmas procesadas |

### Ver también

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
