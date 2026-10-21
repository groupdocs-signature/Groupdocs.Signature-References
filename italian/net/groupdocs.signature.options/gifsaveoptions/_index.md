---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Opzioni di salvataggio in formato GIF per documenti immagine."
type: docs
weight: 1610
url: /it/net/groupdocs.signature.options/gifsaveoptions/
---
## GifSaveOptions class

Opzioni di salvataggio in formato GIF per documenti immagine.

```csharp
public sealed class GifSaveOptions : ImageSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GifSaveOptions](gifsaveoptions)() | Crea GifSaveOptions con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [BackgroundColorIndex](../../groupdocs.signature.options/gifsaveoptions/backgroundcolorindex) { get; set; } | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [ColorResolution](../../groupdocs.signature.options/gifsaveoptions/colorresolution) { get; set; } | Ottiene o imposta la risoluzione colore GIF. |
| [DoPaletteCorrection](../../groupdocs.signature.options/gifsaveoptions/dopalettecorrection) { get; set; } | Ottiene o imposta un valore che indica se viene applicata la correzione della palette. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [HasTrailer](../../groupdocs.signature.options/gifsaveoptions/hastrailer) { get; set; } | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| [Interlaced](../../groupdocs.signature.options/gifsaveoptions/interlaced) { get; set; } | True se l'immagine deve essere interlacciata. |
| [IsPaletteSorted](../../groupdocs.signature.options/gifsaveoptions/ispalettesorted) { get; set; } | Ottiene o imposta un valore che indica se le voci della palette sono ordinate. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso. Per impostazione predefinita questo valore è true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti immagine. |
| [PixelAspectRatio](../../groupdocs.signature.options/gifsaveoptions/pixelaspectratio) { get; set; } | Ottiene o imposta il rapporto d'aspetto dei pixel GIF. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Vedi anche

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
