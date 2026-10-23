---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von PdfSaveOptions mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von PdfSaveOptions mit Standardwerten.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Initialisiert eine neue Instanz von PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat.

```python
def __init__(self, file_format):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Ausgabetyp `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Initialisiert eine neue Instanz von PdfSaveOptions mit einem Überschreibungs-Flag.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |

## __init__ {#file_format-overwrite_existing_file}

Initialisiert eine neue Instanz von PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreibungs-Flag.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Ausgabetyp. |
| overwrite_existing_file | `bool` | Flag, ob die signierte Datei mit derselben Datei überschrieben werden soll. |

### Beispiel

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Speicheroptionen im PDF-Format erstellen und das Überschreiben vorhandener Dateien zulassen
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Siehe auch
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
