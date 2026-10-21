---
title: "VerificationResult"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Istanza per conservare i risultati del processo di verifica."
type: docs
weight: 1240
url: /it/net/groupdocs.signature.domain/verificationresult/
---
## VerificationResult class

Istanza per conservare i risultati del processo di verifica.

```csharp
public class VerificationResult : IResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/verificationresult/destindocumentsize) { get; } | Restituisce la dimensione del documento di destinazione. Per la verifica questa variabile contiene sempre zero. |
| [Failed](../../groupdocs.signature.domain/verificationresult/failed) { get; } | Elenco delle firme che hanno fallito il processo di verifica. Attualmente questa proprietà non è supportata. |
| [IsValid](../../groupdocs.signature.domain/verificationresult/isvalid) { get; } | Restituisce true se il processo di verifica è stato completato con successo, altrimenti false. |
| [ProcessingTime](../../groupdocs.signature.domain/verificationresult/processingtime) { get; } | Restituisce il tempo di esecuzione del processo in millisecondi. |
| [SourceDocumentSize](../../groupdocs.signature.domain/verificationresult/sourcedocumentsize) { get; } | Restituisce la dimensione del documento sorgente in byte |
| [Succeeded](../../groupdocs.signature.domain/verificationresult/succeeded) { get; } | Elenco delle firme verificate con successo [`BaseSignature`](../basesignature). |
| [TotalSignatures](../../groupdocs.signature.domain/verificationresult/totalsignatures) { get; } | Restituisce il totale delle firme elaborate. |

### Vedi anche

* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
