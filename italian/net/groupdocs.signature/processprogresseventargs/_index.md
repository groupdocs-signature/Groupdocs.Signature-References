---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Fornisce i dati per l'evento OnProgress dei processi di verifica della firma e di ricerca."
type: docs
weight: 2130
url: /it/net/groupdocs.signature/processprogresseventargs/
---
## ProcessProgressEventArgs class

Fornisce dati per l'evento OnProgress dei processi di firma, verifica e ricerca.

```csharp
public class ProcessProgressEventArgs : ProcessEventArgs
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ProcessProgressEventArgs](processprogresseventargs)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Cancel](../../groupdocs.signature/processprogresseventargs/cancel) { get; set; } | Indica se il processo deve essere annullato. |
| [ProcessedSignatures](../../groupdocs.signature/processprogresseventargs/processedsignatures) { get; set; } | Rappresenta la quantità di firme elaborate. |
| [Progress](../../groupdocs.signature/processprogresseventargs/progress) { get; set; } | Rappresenta il progresso in percentuale. L'intervallo di valori è da 0 a 100. |
| [Status](../../groupdocs.signature/processeventargs/status) { get; set; } | Indica lo stato corrente del processo. |
| [Ticks](../../groupdocs.signature/processprogresseventargs/ticks) { get; set; } | Rappresenta il tempo trascorso in millisecondi dall'evento Start del processo. |

### Vedi anche

* class [ProcessEventArgs](../processeventargs)
* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
