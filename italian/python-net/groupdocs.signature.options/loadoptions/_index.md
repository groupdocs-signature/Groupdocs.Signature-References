---
title: "Classe LoadOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "La classe LoadOptions consente di specificare opzioni aggiuntive (come la password) durante l'apertura di un documento da firmare."
type: docs
url: /it/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

La classe LoadOptions consente di specificare opzioni aggiuntive (come la password) durante l'apertura di un documento da firmare.

Imposta l'attributo `password` alla password del documento se il file è crittografato.

Il tipo LoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Inizializza una nuova istanza della classe LoadOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Inizializza una nuova istanza della classe [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) con un tipo di file specificato. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Il tipo di file associato alle opzioni di caricamento, impostato di default su [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Il flag che determina se il documento carica risorse esterne. Questa proprietà è obsoleta; usa invece [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), che ha il significato opposto. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | La password utilizzata per aprire un documento protetto e per salvare un documento firmato come protetto. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | Le autorizzazioni del documento PDF, come stampa, modifica ed estrazione dei dati. Solo per documenti PDF. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | Il flag che impedisce al documento di caricare risorse esterne. Il valore predefinito è True; le risorse esterne non vengono caricate eccetto quelle che corrispondono a [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | L'elenco dei frammenti di indirizzo delle risorse esterne che vengono caricati anche quando [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) è true. Il valore predefinito è una lista vuota. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
