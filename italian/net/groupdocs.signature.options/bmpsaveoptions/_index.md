---
title: "BmpSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio BMP per documenti immagine."
type: docs
weight: 1480
url: /it/net/groupdocs.signature.options/bmpsaveoptions/
---
## BmpSaveOptions class

Opzioni di salvataggio BMP per documenti immagine.

```csharp
public sealed class BmpSaveOptions : ImageSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BmpSaveOptions](bmpsaveoptions)() | Crea BmpSaveOptions con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [BitsPerPixel](../../groupdocs.signature.options/bmpsaveoptions/bitsperpixel) { get; set; } | Ottiene o imposta il conteggio dei bit per pixel dell'immagine. |
| [Compression](../../groupdocs.signature.options/bmpsaveoptions/compression) { get; set; } | Ottiene o imposta la compressione. Vedi [`BitmapCompression`](../bitmapcompression). |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [HorizontalResolution](../../groupdocs.signature.options/bmpsaveoptions/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |
| [VerticalResolution](../../groupdocs.signature.options/bmpsaveoptions/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |

### Vedi anche

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
