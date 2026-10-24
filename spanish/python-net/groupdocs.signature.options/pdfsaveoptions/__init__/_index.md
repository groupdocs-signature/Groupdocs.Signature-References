---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de PdfSaveOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de PdfSaveOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Inicializa una nueva instancia de PdfSaveOptions con el formato de archivo de salida especificado.

```python
def __init__(self, file_format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Tipo de archivo de salida `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Inicializa una nueva instancia de PdfSaveOptions con una bandera de sobrescritura.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Bandera que indica si sobrescribir el archivo firmado con el mismo archivo. |

## __init__ {#file_format-overwrite_existing_file}

Inicializa una nueva instancia de PdfSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Tipo de archivo de salida. |
| overwrite_existing_file | `bool` | Bandera que indica si sobrescribir el archivo firmado con el mismo archivo. |

### Ejemplo

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Cree opciones de guardado con formato PDF y permita sobrescribir archivos existentes
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Ver también
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
