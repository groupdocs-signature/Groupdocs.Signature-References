---
title: JpegSaveOptions
second_title: Riferimento API GroupDocs.Signature per .NET
description: Opzioni di salvataggio Jpeg per documenti immagine.
type: docs
weight: 1460
url: /it/net/groupdocs.signature.options/jpegsaveoptions/
---
## JpegSaveOptions class

Opzioni di salvataggio Jpeg per documenti immagine.

```csharp
public sealed class JpegSaveOptions : ImageSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JpegSaveOptions](jpegsaveoptions)() | Crea JpegSaveOptions con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel file di output path Il valore predefinito è false. |
| [BitsPerChannel](../../groupdocs.signature.options/jpegsaveoptions/bitsperchannel) { get; set; } | Ottiene o imposta i bit per canale per l'immagine jpeg senza perdita di dati. Ora supportiamo da 2 a 8 bit per canale. |
| [ColorType](../../groupdocs.signature.options/jpegsaveoptions/colortype) { get; set; } | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
| [Comment](../../groupdocs.signature.options/jpegsaveoptions/comment) { get; set; } | Ottiene o imposta il commento del file jpeg. |
| [CompressionType](../../groupdocs.signature.options/jpegsaveoptions/compressiontype) { get; set; } | Ottiene o imposta il tipo di compressione. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Ottiene o imposta il formato file del documento firmato. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con numero come suffisso. Per impostazione predefinita, questo valore è impostato su true, il che significa che il file verrà sovrascritto. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Ottiene o imposta la password per salvare il documento firmato con protezione tramite password. Questa proprietà non è supportata per i documenti immagine. |
| [Quality](../../groupdocs.signature.options/jpegsaveoptions/quality) { get; set; } | Ottiene o imposta la qualità dell'immagine. |
| [SampleRoundingMode](../../groupdocs.signature.options/jpegsaveoptions/sampleroundingmode) { get; set; } | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit JpegOptions.BitsPerChannel. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Ottiene o imposta se utilizzare la password di LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti immagine. |

### Guarda anche

* class [ImageSaveOptions](../imagesaveoptions)
* spazio dei nomi [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
