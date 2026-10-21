---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio per documenti di Presentazione."
type: docs
weight: 1830
url: /it/net/groupdocs.signature.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Opzioni di salvataggio per documenti di Presentazione.

```csharp
public class PresentationSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | Inizializza una nuova istanza della classe PresentationSaveOptions con valori predefiniti. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(bool) | Inizializza una nuova istanza della classe PresentationSaveOptions con il tipo di output specificato e il flag di sovrascrittura. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_2)(PresentationSaveFileFormat) | Inizializza una nuova istanza della classe PresentationSaveOptions con il formato di file di output specificato. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_3)(PresentationSaveFileFormat, bool) | Inizializza una nuova istanza della classe PresentationSaveOptions con il formato di file di output specificato e il flag di sovrascrittura. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [FileFormat](../../groupdocs.signature.options/presentationsaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Vedi anche

* class [SaveOptions](../saveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
