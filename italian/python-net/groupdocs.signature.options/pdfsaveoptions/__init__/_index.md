---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza di PdfSaveOptions con i valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di PdfSaveOptions con i valori predefiniti.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Inizializza una nuova istanza di PdfSaveOptions con il formato file di output specificato.

```python
def __init__(self, file_format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Tipo file di output `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Inizializza una nuova istanza di PdfSaveOptions con un flag di sovrascrittura.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Flag che indica se sovrascrivere il file firmato con lo stesso file. |

## __init__ {#file_format-overwrite_existing_file}

Inizializza una nuova istanza di PdfSaveOptions con il formato file di output specificato e il flag di sovrascrittura.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Tipo file di output. |
| overwrite_existing_file | `bool` | Flag che indica se sovrascrivere il file firmato con lo stesso file. |

### Esempio

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Crea opzioni di salvataggio con formato PDF e consenti la sovrascrittura dei file esistenti
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Vedi anche
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
