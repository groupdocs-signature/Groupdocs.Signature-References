---
title: "DeleteResult"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Resultado de la eliminación de firmas del documento."
type: docs
weight: 130
url: /es/net/groupdocs.signature.domain/deleteresult/
---
## DeleteResult class

Resultado de la eliminación de firma(s) del documento.

```csharp
public class DeleteResult : IResult
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/deleteresult/destindocumentsize) { get; } | Devuelve el tamaño actualizado del documento. |
| [Failed](../../groupdocs.signature.domain/deleteresult/failed) { get; } | Lista de firmas que no fueron eliminadas [`BaseSignature`](../basesignature). |
| [ProcessingTime](../../groupdocs.signature.domain/deleteresult/processingtime) { get; } | Devuelve el tiempo de ejecución del proceso en milisegundos. |
| [SourceDocumentSize](../../groupdocs.signature.domain/deleteresult/sourcedocumentsize) { get; } | Devuelve el tamaño del documento fuente. |
| [Succeeded](../../groupdocs.signature.domain/deleteresult/succeeded) { get; } | Lista de firmas eliminadas con éxito [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/deleteresult/totalsignatures) { get; } | Devuelve el total de firmas procesadas. |

### Ver también

* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
