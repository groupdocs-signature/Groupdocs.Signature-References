---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av PdfSaveOptions med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av PdfSaveOptions med standardvärden.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Initierar en ny instans av PdfSaveOptions med det angivna utdatafilformatet.

```python
def __init__(self, file_format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Utdatafiltyp `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Initierar en ny instans av PdfSaveOptions med en överskrivningsflagga.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Flagga om den signerade filen ska skrivas över med samma fil. |

## __init__ {#file_format-overwrite_existing_file}

Initierar en ny instans av PdfSaveOptions med det angivna utdatafilformatet och en överskrivningsflagga.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Utdatafiltyp. |
| overwrite_existing_file | `bool` | Flagga om den signerade filen ska skrivas över med samma fil. |

### Exempel

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Skapa sparalternativ med PDF-format och tillåt överskrivning av befintliga filer
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Se även
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
