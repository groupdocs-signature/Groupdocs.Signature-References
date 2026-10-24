---
title: "SaveOptions classe"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Specifica opzioni aggiuntive (come la password) durante il salvataggio di un documento da firmare."
type: docs
url: /it/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Specifica opzioni aggiuntive (come la password) durante il salvataggio di un documento da firmare.

Il tipo SaveOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Inizializza una nuova istanza della classe SaveOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Inizializza una nuova istanza della classe SaveOptions con il tipo di output specificato e il flag di sovrascrittura. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Il flag che determina se aggiungere automaticamente un'estensione quando manca nel percorso del file di output. Il valore predefinito è False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Il flag che indica se sovrascrivere un file esistente con il nuovo file di output. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La password utilizzata per proteggere il documento firmato salvato. Non supportato per i documenti Immagine. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Il flag che indica se utilizzare la password da [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) quando si salva il documento firmato come protetto. Il valore predefinito è True. Non supportato per i documenti Immagine. |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
