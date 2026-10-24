---
title: "classe JpegSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di salvataggio JPEG per i documenti immagine."
type: docs
url: /it/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Rappresenta le opzioni di salvataggio JPEG per i documenti immagine.

Il tipo JpegSaveOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Inizializza JpegSaveOptions con i valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | Il numero di bit per canale per un'immagine JPEG senza perdita. I valori supportati vanno da 2 a 8 bit per canale. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | Il tipo di colore per l'immagine JPEG. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | Il commento del file JPEG. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | Il tipo di compressione. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | La qualità dell'immagine. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | La modalità di arrotondamento del campione usata per adattare un valore a 8 bit a un valore n-bit di `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Il flag che determina se aggiungere automaticamente un'estensione quando manca nel percorso del file di output. Il valore predefinito è False. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Il formato file del documento firmato. (eredita da [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Il flag indica se sovrascrivere un file esistente con il nuovo file di output. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La password utilizzata per proteggere il documento firmato salvato. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Il flag indica se utilizzare la password da [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) durante il salvataggio del documento firmato come protetto. Il valore predefinito è True. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
