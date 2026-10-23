---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine PDF-Metadaten-Signatur mit einem vordefinierten Namen und einem leeren Wert."
type: docs
url: /de/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialisiert eine PDF-Metadaten-Signatur mit einem vordefinierten Namen und einem leeren Wert.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | PDF-Metadaten-Signaturname. |

## __init__ {#name-value}

Initialisiert eine PDF-Metadaten-Signatur mit vordefinierten Werten.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Name des Metadaten-Signaturobjekts. |
| value | `Any` | Wert der Metadaten-Signatur. |

### Beispiel

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Initialisiert eine PDF-Metadaten-Signatur mit vordefinierten Werten.

```python
def __init__(self, name, value, tag):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Name des Metadaten-Signaturobjekts. |
| value | `Any` | Wert der Metadaten-Signatur. |
| tag | `str` | Präfix-Tag der Metadaten-Signatur. |

### Beispiel

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Erstellen Sie eine Metadaten-Signatur für den PDF-Autor
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Erstellen Sie eine Metadaten-Signatur für das Erstellungsdatum
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Erstellen Sie eine Metadaten-Signatur für einen numerischen Bezeichner
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Erstellen Sie eine Metadaten-Signatur für einen Gleitkommawert
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Siehe auch
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
