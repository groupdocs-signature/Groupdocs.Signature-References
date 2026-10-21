---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio per documenti Spreadsheet."
type: docs
weight: 1990
url: /it/net/groupdocs.signature.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Opzioni di salvataggio per documenti Spreadsheet.

```csharp
public class SpreadsheetSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Inizializza una nuova istanza della classe SpreadsheetSaveOptions con valori predefiniti. |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetSaveFileFormat) | Inizializza una nuova istanza della classe SpreadsheetSaveOptions con formato di file di output predefinito. |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_2)(SpreadsheetSaveFileFormat, bool) | Inizializza una nuova istanza della classe SpreadsheetSaveOptions con tipo di output specificato e flag di sovrascrittura. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [FileFormat](../../groupdocs.signature.options/spreadsheetsaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Vedi anche

* class [SaveOptions](../saveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
