---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Fornisce dati sull'evento di completamento dei processi di verifica della firma e di ricerca."
type: docs
weight: 2100
url: /it/net/groupdocs.signature/processcompleteeventargs/
---
## ProcessCompleteEventArgs class

Fornisce dati sull'evento di completamento dei processi di firma, verifica e ricerca.

```csharp
public class ProcessCompleteEventArgs : ProcessEventArgs
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Canceled](../../groupdocs.signature/processcompleteeventargs/canceled) { get; } | Indica se il processo è stato annullato. |
| [Completed](../../groupdocs.signature/processcompleteeventargs/completed) { get; set; } | Rappresenta il timestamp di completamento del processo. |
| [Status](../../groupdocs.signature/processeventargs/status) { get; set; } | Indica lo stato corrente del processo. |
| [Ticks](../../groupdocs.signature/processcompleteeventargs/ticks) { get; set; } | Rappresenta il tempo in millisecondi trascorso dall'evento di avvio del processo. |
| [TotalSignatures](../../groupdocs.signature/processcompleteeventargs/totalsignatures) { get; set; } | Rappresenta la quantità totale di firme elaborate. |

### Vedi anche

* class [ProcessEventArgs](../processeventargs)
* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
