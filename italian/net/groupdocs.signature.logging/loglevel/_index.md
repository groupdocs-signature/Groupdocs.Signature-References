---
title: "LogLevel"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Specifica quali tipi di messaggi vengono passati al logger impostato in SignatureSettings../groupdocs.signature/signaturesettings. I valori sono flag e possono essere combinati, ad esempio LogLevel.Error  LogLevel.Warning."
type: docs
weight: 1360
url: /it/net/groupdocs.signature.logging/loglevel/
---
## LogLevel enumeration

Specifica quali tipi di messaggi vengono passati al logger impostato in [`SignatureSettings`](../../groupdocs.signature/signaturesettings). I valori sono flag e possono essere combinati, ad esempio `LogLevel.Error | LogLevel.Warning`.

```csharp
[Flags]
public enum LogLevel
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Niente viene registrato. |
| Error | `1` | Errori: un'operazione è fallita. |
| Warning | `2` | Avvisi: un'operazione è riuscita, ma il suo risultato potrebbe non essere quello che ti aspetti. |
| Trace | `4` | Tracce: i passaggi di un'operazione, come l'inizio e la fine. |
| All | `7` | Errori, avvisi e tracce. Questo è il valore predefinito. |

### Vedi anche

* namespace [GroupDocs.Signature.Logging](../../groupdocs.signature.logging)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
