---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio per documenti di elaborazione testi."
type: docs
weight: 2080
url: /it/net/groupdocs.signature.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Opzioni di salvataggio per documenti di elaborazione testi.

```csharp
public class WordProcessingSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Inizializza una nuova istanza della classe WordProcessingSaveOptions con valori predefiniti. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(bool) | Inizializza una nuova istanza della classe WordProcessingSaveOptions con tipo di output specificato e flag di sovrascrittura. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_2)(WordProcessingSaveFileFormat) | Inizializza una nuova istanza della classe WordProcessingSaveOptions con formato di file di output specificato. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_3)(WordProcessingSaveFileFormat, bool) | Inizializza una nuova istanza della classe WordProcessingSaveOptions con formato di file di output specificato e flag di sovrascrittura. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [FileFormat](../../groupdocs.signature.options/wordprocessingsaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [OoxmlCompliance](../../groupdocs.signature.options/wordprocessingsaveoptions/ooxmlcompliance) { get; set; } | Livello opzionale di conformità OOXML per il documento firmato. Quando impostato, sovrascrive la conformità del documento originale. Quando nullo (predefinito), la conformità del documento caricato viene preservata. Valido solo per i formati OOXML (Docx, Docm, Dotx, Dotm, FlatOpc e varianti FlatOpc). |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Vedi anche

* class [SaveOptions](../saveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
