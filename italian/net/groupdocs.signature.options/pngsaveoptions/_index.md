---
title: "PngSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio PNG per documenti immagine."
type: docs
weight: 1820
url: /it/net/groupdocs.signature.options/pngsaveoptions/
---
## PngSaveOptions class

Opzioni di salvataggio PNG per documenti immagine.

```csharp
public sealed class PngSaveOptions : ImageSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PngSaveOptions](pngsaveoptions)() | Crea PngSaveOptions con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [BitDepth](../../groupdocs.signature.options/pngsaveoptions/bitdepth) { get; set; } | La profondità di bit. |
| [ColorType](../../groupdocs.signature.options/pngsaveoptions/colortype) { get; set; } | Ottiene o imposta il tipo di [`PngColorType`](../pngcolortype). |
| [CompressionLevel](../../groupdocs.signature.options/pngsaveoptions/compressionlevel) { get; set; } | Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è compressione massima e 0 è modalità di archiviazione. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [FilterType](../../groupdocs.signature.options/pngsaveoptions/filtertype) { get; set; } | Ottiene o imposta il tipo di filtro [`PngFilterType`](../pngfiltertype) utilizzato durante il processo di salvataggio del file png. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [Progressive](../../groupdocs.signature.options/pngsaveoptions/progressive) { get; set; } | Ottiene o imposta un valore che indica se questo PngSaveOptions è progressivo. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Vedi anche

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
