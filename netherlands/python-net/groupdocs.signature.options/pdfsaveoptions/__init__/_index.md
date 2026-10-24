---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van PdfSaveOptions met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van PdfSaveOptions met standaardwaarden.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Initialiseert een nieuw exemplaar van PdfSaveOptions met het opgegeven uitvoerbestandsformaat.

```python
def __init__(self, file_format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Uitvoer bestandstype `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Initialiseert een nieuw exemplaar van PdfSaveOptions met een overschrijvingsvlag.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Vlag die aangeeft of het ondertekende bestand moet worden overschreven met hetzelfde bestand. |

## __init__ {#file_format-overwrite_existing_file}

Initialiseert een nieuw exemplaar van PdfSaveOptions met het opgegeven uitvoerbestandsformaat en overschrijvingsvlag.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Uitvoer bestandstype. |
| overwrite_existing_file | `bool` | Vlag die aangeeft of het ondertekende bestand moet worden overschreven met hetzelfde bestand. |

### Voorbeeld

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Maak opslaanopties met PDF-formaat en sta het overschrijven van bestaande bestanden toe
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Zie ook
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
