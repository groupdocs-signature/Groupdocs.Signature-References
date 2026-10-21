---
title: "LoadOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Consente di specificare opzioni aggiuntive come la password quando si apre un documento da firmare."
type: docs
weight: 1720
url: /it/net/groupdocs.signature.options/loadoptions/
---
## LoadOptions class

Consente di specificare opzioni aggiuntive (come la password) durante l'apertura di un documento da firmare.

```csharp
public class LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Inizializza una nuova istanza della classe LoadOptions. |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Inizializza una nuova istanza della classe [`LoadOptions`](../loadoptions) con un tipo di file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FileType](../../groupdocs.signature.options/loadoptions/filetype) { get; set; } | Ottiene o imposta il tipo di file associato alle opzioni di caricamento. |
| [Password](../../groupdocs.signature.options/loadoptions/password) { get; set; } | Ottiene o imposta la password per aprire un documento protetto. Verrà inoltre utilizzata per salvare il documento firmato come protetto. |
| [Permissions](../../groupdocs.signature.options/loadoptions/permissions) { get; } | Le autorizzazioni del documento PDF, come stampa, modifica ed estrazione dei dati. Solo per documenti PDF. |
| [SkipExternalResources](../../groupdocs.signature.options/loadoptions/skipexternalresources) { get; set; } | Ottiene o imposta un flag che impedisce al documento di caricare risorse esterne. Il valore predefinito è true: le risorse esterne non vengono caricate, eccetto quelle che corrispondono a [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.signature.options/loadoptions/whitelistedresources) { get; set; } | Ottiene o imposta frammenti di indirizzi di risorse esterne che vengono caricati anche quando [`SkipExternalResources`](./skipexternalresources) è true. Il valore predefinito è una lista vuota. |

### Vedi anche

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
