---
title: "SearchResult"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Risultato della ricerca delle firme nel documento specificato."
type: docs
weight: 1010
url: /it/net/groupdocs.signature.domain/searchresult/
---
## SearchResult class

Risultato della ricerca delle firme nel documento specificato.

```csharp
public class SearchResult : IEnumerable<BaseSignature>, IResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/searchresult/destindocumentsize) { get; } | Restituisce la dimensione del documento di destinazione. Per il metodo Search restituisce sempre 0. |
| [Failed](../../groupdocs.signature.domain/searchresult/failed) { get; } | Elenco di firme [`BaseSignature`](../basesignature) che hanno fallito il processo di ricerca per criterio di ricerca. Supportato solo per documenti archivio falliti nel metodo Search. |
| [ProcessingTime](../../groupdocs.signature.domain/searchresult/processingtime) { get; } | Restituisce il tempo di esecuzione del processo di ricerca in millisecondi. |
| [Signatures](../../groupdocs.signature.domain/searchresult/signatures) { get; } | Elenco delle firme trovate [`BaseSignature`](../basesignature). |
| [SourceDocumentSize](../../groupdocs.signature.domain/searchresult/sourcedocumentsize) { get; } | Restituisce la dimensione del documento di origine. |
| [Succeeded](../../groupdocs.signature.domain/searchresult/succeeded) { get; } | Elenco delle firme trovate [`BaseSignature`](../basesignature). Questo elenco sarà sempre uguale alla proprietà [`Signatures`](./signatures). |
| [TotalSignatures](../../groupdocs.signature.domain/searchresult/totalsignatures) { get; } | Restituisce il totale delle firme elaborate dal processo di ricerca |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetEnumerator](../../groupdocs.signature.domain/searchresult/getenumerator)() | Restituisce l'enumeratore. |
| [ToList&lt;T&gt;](../../groupdocs.signature.domain/searchresult/tolist)() | Fornisce la conversione a un elenco tipizzato di firme. |

### Vedi anche

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
