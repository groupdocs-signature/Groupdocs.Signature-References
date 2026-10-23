---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Signature‑Instanz mit einem als Stream bereitgestellten Dokument."
type: docs
url: /de/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Initialisiert eine neue Signature‑Instanz mit einem als Stream bereitgestellten Dokument.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Dokumenten-Inhaltsstream. |

## __init__ {#document-load_options}

Initialisiert eine neue [`Signature`](/signature/python-net/groupdocs.signature/signature/)‑Instanz mit einem Dokument‑Stream und Ladeoptionen.

Mehr erfahren

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Dokumenten-Inhaltsstream. |
| load_options | `LoadOptions` | Die Dokumenten-Ladeoptionen. |

## __init__ {#document-settings}

Initialisiert eine neue [`Signature`](/signature/python-net/groupdocs.signature/signature/)‑Instanz mit einem durch einen Stream bereitgestellten Dokument und optionalen [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Mehr erfahren:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Dokumenten-Inhaltsstream. |
| settings | `SignatureSettings` | Die Signatur-Einstellungen. |

## __init__ {#document-load_options-settings}

Initialisiert eine neue Instanz von [`Signature`](/signature/python-net/groupdocs.signature/signature/) mit einem Dokument‑Stream, Ladeoptionen und Signatur‑Einstellungen.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Dokumenten-Inhaltsstream. |
| load_options | `LoadOptions` | Die Dokumenten-Ladeoptionen. |
| settings | `SignatureSettings` | Die Signatur-Einstellungen. |

## __init__ {#file_path}

Initialisiert eine neue Instanz von [`Signature`](/signature/python-net/groupdocs.signature/signature/) mit einem durch Dateipfad bereitgestellten Dokument.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Absoluter oder relativer Dateipfad. |

### Beispiel

```python
from groupdocs.signature import Signature

# Ein Dokument zum Signieren, Suchen oder Verifizieren öffnen
with Signature("sample.pdf") as signature:
    # mit dem Signatur-Objekt arbeiten
    pass
```

## __init__ {#file_path-load_options}

Initialisiert eine neue Signature‑Instanz mit dem durch Dateipfad bereitgestellten Dokument und Ladeoptionen.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Absoluter oder relativer Dateipfad. |
| load_options | `LoadOptions` | Die Dokumenten-Ladeoptionen. |

### Beispiel

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Signier-, Such- oder Verifizierungsvorgänge ausführen
    pass
```

## __init__ {#file_path-settings}

Initialisiert eine neue [`Signature`](/signature/python-net/groupdocs.signature/signature/)‑Instanz mit dem durch einen Dateipfad bereitgestellten Dokument und optionalen [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Absoluter oder relativer Dateipfad. |
| settings | `SignatureSettings` | Die Signatur-Einstellungen. |

### Beispiel

```python
from groupdocs.signature import Signature

# Ein PDF-Dokument zum Signieren oder Verifizieren öffnen
with Signature("sample.pdf") as signature:
    # Verwenden Sie hier die Signaturinstanz (z. B. sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

Initialisiert eine neue Instanz von [`Signature`](/signature/python-net/groupdocs.signature/signature/) mit einem durch Dateipfad bereitgestellten Dokument, Ladeoptionen und Signatur‑Einstellungen.

Mehr erfahren:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Absoluter oder relativer Dateipfad. |
| load_options | `LoadOptions` | Die Dokumenten-Ladeoptionen. |
| settings | `SignatureSettings` | Die Signatur-Einstellungen. |

### Beispiel

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Signier-, Verifizierungs- oder Suchvorgänge ausführen
    pass
```

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
