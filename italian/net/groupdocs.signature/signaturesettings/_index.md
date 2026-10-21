---
title: "SignatureSettings"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Definisce le impostazioni per personalizzare il comportamento di Signature./signature."
type: docs
weight: 2180
url: /it/net/groupdocs.signature/signaturesettings/
---
## SignatureSettings class

Definisce le impostazioni per personalizzare il comportamento di [`Signature`](../signature).

```csharp
public class SignatureSettings
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SignatureSettings](signaturesettings#constructor)() | Crea un'istanza predefinita di SignatureSettings con valori predefiniti. |
| [SignatureSettings](signaturesettings#constructor_1)(ILogger) | Crea un'istanza predefinita di SignatureSettings con l'implementazione Logger. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DefaultCulture](../../groupdocs.signature/signaturesettings/defaultculture) { get; set; } | Ottiene o imposta la cultura predefinita da utilizzare durante l'elaborazione dei documenti. Il valore predefinito è "en-US". |
| [IncludeStandardMetadataSignatures](../../groupdocs.signature/signaturesettings/includestandardmetadatasignatures) { get; set; } | Ottiene o imposta il flag per includere nella Lista dei Metadati le firme di metadati standard del documento incorporate, come Autore, Proprietario, data di creazione del documento, data di modifica, ecc. Se questo flag è impostato su false (per impostazione predefinita) GetDocumentInfo non includerà queste firme di metadati. Quando questo flag è impostato su true le informazioni del documento includeranno queste firme di metadati standard. |
| [Logger](../../groupdocs.signature/signaturesettings/logger) { get; } | L'implementazione del logger utilizzata per la registrazione (Errori, Avvisi, Tracce). [`ILogger`](../../groupdocs.signature.logging/ilogger). |
| [LogLevel](../../groupdocs.signature/signaturesettings/loglevel) { get; set; } | Gets or sets which kinds of messages are passed to [`Logger`](./logger). The value is a set of [`LogLevel`](../../groupdocs.signature.logging/loglevel) flags that can be combined, for example `LogLevel.Error | `LogLevel.Warning`. `LogLevel.None` non registra nulla. Il valore predefinito è `LogLevel.All`: errori, avvisi e tracce. |
| [SaveDocumentOnEmptyDelete](../../groupdocs.signature/signaturesettings/savedocumentonemptydelete) { get; set; } | Ottiene o imposta il flag per risalvare il documento sorgente quando il metodo Delete non ha firme da rimuovere. Se questo flag è impostato su true (per impostazione predefinita) il documento verrà salvato con il relativo registro di processo storico (data e tipo di operazione) anche se il metodo Delete non ha firme da rimuovere. Quando questo flag è impostato su false il documento sorgente non verrà modificato affatto. |
| [SaveDocumentOnEmptyUpdate](../../groupdocs.signature/signaturesettings/savedocumentonemptyupdate) { get; set; } | Ottiene o imposta il flag per risalvare il documento sorgente quando il metodo Update non ha firme da aggiornare. Se questo flag è impostato su true (per impostazione predefinita) il documento verrà salvato con il relativo registro di processo storico (data e tipo di operazione) anche se il metodo Update non ha firme da aggiornare. Quando questo flag è impostato su false il documento sorgente non verrà modificato affatto. |
| [ShowDeletedSignaturesInfo](../../groupdocs.signature/signaturesettings/showdeletedsignaturesinfo) { get; set; } | Ottiene o imposta il flag che include le firme eliminate nel risultato delle informazioni del documento. Ogni firma [`BaseSignature`](../../groupdocs.signature.domain/basesignature) ha il flag Deleted [`Deleted`](../../groupdocs.signature.domain/basesignature/deleted) per rilevare se è stata eliminata. |

### Vedi anche

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
