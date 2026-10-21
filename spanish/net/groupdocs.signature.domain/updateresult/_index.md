---
title: "UpdateResult"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Resultado de la modificación de firmas en el documento."
type: docs
weight: 1230
url: /es/net/groupdocs.signature.domain/updateresult/
---
## UpdateResult class

Resultado de la modificación de firmas en el documento.

```csharp
public class UpdateResult : IResult
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/updateresult/destindocumentsize) { get; } | Devuelve el tamaño del documento de destino |
| [Failed](../../groupdocs.signature.domain/updateresult/failed) { get; } | Lista de firmas que no se actualizaron [`BaseSignature`](../basesignature). |
| [ProcessingTime](../../groupdocs.signature.domain/updateresult/processingtime) { get; } | Devuelve el tiempo de ejecución del proceso en milisegundos |
| [SourceDocumentSize](../../groupdocs.signature.domain/updateresult/sourcedocumentsize) { get; } | Devuelve el tamaño del documento de origen |
| [Succeeded](../../groupdocs.signature.domain/updateresult/succeeded) { get; } | Lista de firmas modificadas con éxito [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/updateresult/totalsignatures) { get; } | Devuelve el total de firmas procesadas |

### Ver también

* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
