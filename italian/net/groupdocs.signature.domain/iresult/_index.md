---
title: "IResult"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Interfaccia comune per il risultato del processo di firma."
type: docs
weight: 700
url: /it/net/groupdocs.signature.domain/iresult/
---
## IResult interface

Interfaccia comune per il risultato del processo di firma.

```csharp
public interface IResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/iresult/destindocumentsize) { get; } | Restituisce la dimensione del documento di destinazione. |
| [Failed](../../groupdocs.signature.domain/iresult/failed) { get; } | Elenco delle firme che non sono state elaborate [`BaseSignature`](../basesignature). |
| [ProcessingTime](../../groupdocs.signature.domain/iresult/processingtime) { get; } | Restituisce il tempo di esecuzione del processo in millisecondi. |
| [SourceDocumentSize](../../groupdocs.signature.domain/iresult/sourcedocumentsize) { get; } | Restituisce la dimensione del documento di origine. |
| [Succeeded](../../groupdocs.signature.domain/iresult/succeeded) { get; } | Elenco delle firme elaborate con successo [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/iresult/totalsignatures) { get; } | Restituisce il totale delle firme elaborate. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
