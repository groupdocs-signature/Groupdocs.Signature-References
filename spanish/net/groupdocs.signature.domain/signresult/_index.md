---
title: "SignResult"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Resultado del proceso de firma del documento con firmas recién creadas."
type: docs
weight: 1030
url: /es/net/groupdocs.signature.domain/signresult/
---
## SignResult class

Resultado del proceso de firma del documento con firmas recién creadas.

```csharp
public class SignResult : IResult
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/signresult/destindocumentsize) { get; } | Devuelve el tamaño del documento de destino |
| [Failed](../../groupdocs.signature.domain/signresult/failed) { get; } | Lista de firmas que fallaron al crear. |
| [ProcessingTime](../../groupdocs.signature.domain/signresult/processingtime) { get; } | Devuelve el tiempo de ejecución del proceso en milisegundos |
| [SourceDocumentSize](../../groupdocs.signature.domain/signresult/sourcedocumentsize) { get; } | Devuelve el tamaño del documento de origen |
| [Succeeded](../../groupdocs.signature.domain/signresult/succeeded) { get; } | Lista de firmas recién creadas [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/signresult/totalsignatures) { get; } | Devuelve el total de firmas procesadas |

### Ver también

* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
