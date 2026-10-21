---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio per documenti PDF."
type: docs
weight: 1760
url: /it/net/groupdocs.signature.options/pdfsaveoptions/
---
## PdfSaveOptions class

Opzioni di salvataggio per documenti PDF.

```csharp
public class PdfSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions#constructor)() | Inizializza una nuova istanza della classe PdfSaveOptions con valori predefiniti. |
| [PdfSaveOptions](pdfsaveoptions#constructor_1)(bool) | Inizializza una nuova istanza della classe PdfSaveOptions con flag di sovrascrittura. |
| [PdfSaveOptions](pdfsaveoptions#constructor_2)(PdfSaveFileFormat) | Inizializza una nuova istanza della classe PdfSaveOptions con il formato di file di output specificato. |
| [PdfSaveOptions](pdfsaveoptions#constructor_3)(PdfSaveFileFormat, bool) | Inizializza una nuova istanza della classe PdfSaveOptions con il formato di file di output specificato e il flag di sovrascrittura. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [FileFormat](../../groupdocs.signature.options/pdfsaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [Permissions](../../groupdocs.signature.options/pdfsaveoptions/permissions) { get; set; } | Le autorizzazioni del documento PDF come stampa, modifica ed estrazione dati. |
| [PermissionsPassword](../../groupdocs.signature.options/pdfsaveoptions/permissionspassword) { get; set; } | Una password di autorizzazione (la password primaria) richiede una password per modificare le impostazioni di autorizzazione. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Vedi anche

* class [SaveOptions](../saveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
