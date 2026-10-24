---
title: "Classe ExportImageSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di salvataggio per l'esportazione dei documenti in immagine."
type: docs
url: /it/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Rappresenta le opzioni di salvataggio per l'esportazione dei documenti in immagine.

Il tipo ExportImageSaveOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Inizializza una nuova istanza della classe ExportAsImageSaveOptions con i valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Inizializza una nuova istanza di ExportAsImageSaveOptions con il formato file specificato. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | Le impostazioni del bordo dell'immagine. Per impostazione predefinita questo valore non è impostato. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | Il flag per esportare ogni pagina. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Il numero di colonne per le immagini esportate. Usa questa proprietà se devi posizionare le immagini in una riga. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Il numero di pagina del documento da esportare (il valore minimo è 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | Le opzioni per specificare le pagine da firmare. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Le pagine del documento sono collocate su fotogrammi diversi in un'immagine TIFF. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Il flag che determina se aggiungere automaticamente un'estensione quando manca nel percorso del file di output. Il valore predefinito è False. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Il formato file del documento firmato. (eredita da [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Il flag indica se sovrascrivere un file esistente con il nuovo file di output. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La password utilizzata per proteggere il documento firmato salvato. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Il flag indica se utilizzare la password da [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) durante il salvataggio del documento firmato come protetto. Il valore predefinito è True. Non supportato per i documenti Image. (eredita da [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
