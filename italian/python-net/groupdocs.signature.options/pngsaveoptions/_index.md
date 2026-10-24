---
title: "classe PngSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Le opzioni di salvataggio PNG per i documenti immagine."
type: docs
url: /it/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

Le opzioni di salvataggio PNG per i documenti immagine.

Il tipo PngSaveOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | Inizializza PngSaveOptions con valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | La profondità di bit. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | Il tipo di `PngColorType`. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è compressione massima e 0 è modalità di archiviazione. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | Il tipo di filtro `PngFilterType` utilizzato durante il processo di salvataggio del file PNG. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | Il flag progressivo che indica se il PNG viene salvato in modo progressivo. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Il flag che determina se aggiungere automaticamente un'estensione quando manca nel percorso del file di output. Il valore predefinito è False. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Il formato file del documento firmato. (eredita da [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Il flag indica se sovrascrivere un file esistente con il nuovo file di output. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La password utilizzata per proteggere il documento firmato salvato. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Il flag indica se utilizzare la password da [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) durante il salvataggio del documento firmato come protetto. Il valore predefinito è True. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
