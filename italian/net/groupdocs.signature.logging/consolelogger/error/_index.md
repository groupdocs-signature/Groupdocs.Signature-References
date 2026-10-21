---
title: "Error"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Scrive un messaggio di errore sulla console. I messaggi di log di errore forniscono informazioni su eventi irrecuperabili nel flusso dell'applicazione."
type: docs
weight: 20
url: /it/net/groupdocs.signature.logging/consolelogger/error/
---
## ConsoleLogger.Error method

Scrive un messaggio di errore sulla console. I messaggi di log di errore forniscono informazioni su eventi irrecuperabili nel flusso dell'applicazione.

```csharp
public void Error(string message, Exception ex)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| message | String | Il messaggio di errore. |
| ex | Eccezione | L'eccezione. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Generata quando *message* è nullo. |
| ArgumentNullException | Lanciata quando *ex* è nullo. |

### Vedi anche

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Signature.Logging](../../../groupdocs.signature.logging)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
