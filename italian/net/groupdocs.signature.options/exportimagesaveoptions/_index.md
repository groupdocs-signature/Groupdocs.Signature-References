---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio per l'esportazione dei documenti in immagine."
type: docs
weight: 1580
url: /it/net/groupdocs.signature.options/exportimagesaveoptions/
---
## ExportImageSaveOptions class

Opzioni di salvataggio per l'esportazione dei documenti in immagine.

```csharp
public class ExportImageSaveOptions : ImageSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor)() | Inizializza una nuova istanza della classe ExportAsImageSaveOptions con valori predefiniti. |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor_1)(ImageSaveFileFormat) | Inizializza una nuova istanza della classe ExportAsImageSaveOptions con il formato file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [Border](../../groupdocs.signature.options/exportimagesaveoptions/border) { get; set; } | Ottiene o imposta le impostazioni del bordo dell'immagine. Per impostazione predefinita questo valore non è impostato. |
| [ExportAllPages](../../groupdocs.signature.options/exportimagesaveoptions/exportallpages) { get; set; } | Flag per esportare ogni pagina. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [PageColumns](../../groupdocs.signature.options/exportimagesaveoptions/pagecolumns) { get; set; } | Ottiene o imposta il numero di colonne per le immagini esportate. Usa questa proprietà se devi mettere le immagini in una riga. |
| [PageNumber](../../groupdocs.signature.options/exportimagesaveoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per l'esportazione. Il valore minimo è 1. |
| [PagesSetup](../../groupdocs.signature.options/exportimagesaveoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [TiffMultipage](../../groupdocs.signature.options/exportimagesaveoptions/tiffmultipage) { get; set; } | Posiziona le pagine del documento su fotogrammi diversi nell'immagine Tiff. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Vedi anche

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
