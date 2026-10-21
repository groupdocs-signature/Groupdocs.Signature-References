---
title: "VerificationResult"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Instancia para mantener los resultados del proceso de verificación."
type: docs
weight: 1240
url: /es/net/groupdocs.signature.domain/verificationresult/
---
## VerificationResult class

Instancia para mantener los resultados del proceso de verificación.

```csharp
public class VerificationResult : IResult
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/verificationresult/destindocumentsize) { get; } | Devuelve el tamaño del documento de destino. Para la verificación, esta variable siempre contiene cero. |
| [Failed](../../groupdocs.signature.domain/verificationresult/failed) { get; } | Lista de firmas que fallaron en el proceso de verificación. Actualmente esta propiedad no es compatible. |
| [IsValid](../../groupdocs.signature.domain/verificationresult/isvalid) { get; } | Devuelve true si el proceso de verificación fue exitoso, de lo contrario false. |
| [ProcessingTime](../../groupdocs.signature.domain/verificationresult/processingtime) { get; } | Devuelve el tiempo de ejecución del proceso en milisegundos. |
| [SourceDocumentSize](../../groupdocs.signature.domain/verificationresult/sourcedocumentsize) { get; } | Devuelve el tamaño del documento fuente en bytes |
| [Succeeded](../../groupdocs.signature.domain/verificationresult/succeeded) { get; } | Lista de firmas verificadas con éxito [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/verificationresult/totalsignatures) { get; } | Devuelve el total de firmas procesadas |

### Ver también

* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
