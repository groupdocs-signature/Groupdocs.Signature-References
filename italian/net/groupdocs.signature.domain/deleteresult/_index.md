---
title: "DeleteResult"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Risultato dell'eliminazione delle firme dal documento."
type: docs
weight: 130
url: /it/net/groupdocs.signature.domain/deleteresult/
---
## DeleteResult class

Risultato dell'eliminazione della/e firma/e dal documento.

```csharp
public class DeleteResult : IResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/deleteresult/destindocumentsize) { get; } | Restituisce la dimensione aggiornata del documento. |
| [Failed](../../groupdocs.signature.domain/deleteresult/failed) { get; } | Elenco delle firme che non sono state eliminate [`BaseSignature`](../basesignature). |
| [ProcessingTime](../../groupdocs.signature.domain/deleteresult/processingtime) { get; } | Restituisce il tempo di esecuzione del processo in millisecondi. |
| [SourceDocumentSize](../../groupdocs.signature.domain/deleteresult/sourcedocumentsize) { get; } | Restituisce la dimensione del documento sorgente. |
| [Succeeded](../../groupdocs.signature.domain/deleteresult/succeeded) { get; } | Elenco delle firme eliminate con successo [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/deleteresult/totalsignatures) { get; } | Restituisce il totale delle firme elaborate. |

### Vedi anche

* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
