---
title: "classe ImageSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di salvataggio per i documenti immagine."
type: docs
url: /it/python-net/groupdocs.signature.options/imagesaveoptions/
is_root: false
weight: 230
---


## ImageSaveOptions class

Rappresenta le opzioni di salvataggio per i documenti immagine.

Il tipo ImageSaveOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/) | Inizializza una nuova istanza della classe ImagesSaveOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#overwrite_existing_file) | Inizializza una nuova istanza della classe ImagesSaveOptions con il flag di sovrascrittura. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#file_format-overwrite_existing_file) | Inizializza una nuova istanza di ImagesSaveOptions con il formato di file di output specificato e il flag di sovrascrittura. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Il formato file del documento firmato. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Il flag che determina se aggiungere automaticamente un'estensione quando manca nel percorso del file di output. Il valore predefinito è False. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Il flag indica se sovrascrivere un file esistente con il nuovo file di output. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La password utilizzata per proteggere il documento firmato salvato. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Il flag indica se utilizzare la password da [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) durante il salvataggio del documento firmato come protetto. Il valore predefinito è True. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
