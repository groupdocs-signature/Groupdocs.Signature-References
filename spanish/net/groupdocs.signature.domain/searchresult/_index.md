---
title: "SearchResult"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Resultado de la búsqueda de firmas en el documento especificado."
type: docs
weight: 1010
url: /es/net/groupdocs.signature.domain/searchresult/
---
## SearchResult class

Resultado de la búsqueda de firmas en el documento especificado.

```csharp
public class SearchResult : IEnumerable<BaseSignature>, IResult
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/searchresult/destindocumentsize) { get; } | Devuelve el tamaño del documento de destino. Para el método Search siempre devuelve 0. |
| [Failed](../../groupdocs.signature.domain/searchresult/failed) { get; } | Lista de firmas [`BaseSignature`](../basesignature) que fallaron en el proceso de búsqueda por criterios de búsqueda. Solo compatible con documentos Archive fallidos en el método Search. |
| [ProcessingTime](../../groupdocs.signature.domain/searchresult/processingtime) { get; } | Devuelve el tiempo de ejecución del proceso de búsqueda en milisegundos. |
| [Signatures](../../groupdocs.signature.domain/searchresult/signatures) { get; } | Lista de firmas encontradas [`BaseSignature`](../basesignature). |
| [SourceDocumentSize](../../groupdocs.signature.domain/searchresult/sourcedocumentsize) { get; } | Devuelve el tamaño del documento de origen |
| [Succeeded](../../groupdocs.signature.domain/searchresult/succeeded) { get; } | Lista de firmas encontradas [`BaseSignature`](../basesignature). Esta lista siempre será igual a la propiedad [`Signatures`](./signatures). |
| [TotalSignatures](../../groupdocs.signature.domain/searchresult/totalsignatures) { get; } | Devuelve el total de firmas procesadas por el proceso de búsqueda |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEnumerator](../../groupdocs.signature.domain/searchresult/getenumerator)() | Devuelve enumerador. |
| [ToList&lt;T&gt;](../../groupdocs.signature.domain/searchresult/tolist)() | Proporciona conversión a una lista de firmas fuertemente tipada. |

### Ver también

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
