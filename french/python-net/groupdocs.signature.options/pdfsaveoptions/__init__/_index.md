---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de PdfSaveOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de PdfSaveOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Initialise une nouvelle instance de PdfSaveOptions avec le format de fichier de sortie spécifié.

```python
def __init__(self, file_format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Type de fichier de sortie `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Initialise une nouvelle instance de PdfSaveOptions avec un drapeau d'écrasement.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Indicateur indiquant s'il faut écraser le fichier signé avec le même fichier. |

## __init__ {#file_format-overwrite_existing_file}

Initialise une nouvelle instance de PdfSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Type de fichier de sortie. |
| overwrite_existing_file | `bool` | Indicateur indiquant s'il faut écraser le fichier signé avec le même fichier. |

### Exemple

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Créez des options d'enregistrement au format PDF et autorisez l'écrasement des fichiers existants
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Voir aussi
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
