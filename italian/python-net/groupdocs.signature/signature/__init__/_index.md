---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza di Signature con un documento fornito come stream."
type: docs
url: /it/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Inizializza una nuova istanza di Signature con un documento fornito come stream.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso di contenuto del documento. |

## __init__ {#document-load_options}

Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con uno stream del documento e opzioni di caricamento.

Maggiori informazioni

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso di contenuto del documento. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |

## __init__ {#document-settings}

Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento fornito tramite stream e opzionale [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Per saperne di più:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso di contenuto del documento. |
| settings | `SignatureSettings` | Le impostazioni della firma. |

## __init__ {#document-load_options-settings}

Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con uno stream del documento, opzioni di caricamento e impostazioni di firma.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso di contenuto del documento. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |
| settings | `SignatureSettings` | Le impostazioni della firma. |

## __init__ {#file_path}

Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento fornito tramite percorso file.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Percorso file assoluto o relativo. |

### Esempio

```python
from groupdocs.signature import Signature

# Apri un documento per la firma, la ricerca o la verifica
with Signature("sample.pdf") as signature:
    # lavora con l'oggetto firma
    pass
```

## __init__ {#file_path-load_options}

Inizializza una nuova istanza di Signature con il documento fornito tramite percorso file e opzioni di caricamento.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Percorso file assoluto o relativo. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |

### Esempio

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Esegui operazioni di firma, ricerca o verifica
    pass
```

## __init__ {#file_path-settings}

Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con il documento fornito tramite percorso file e opzionale [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Percorso file assoluto o relativo. |
| settings | `SignatureSettings` | Le impostazioni della firma. |

### Esempio

```python
from groupdocs.signature import Signature

# Apri un documento PDF per la firma o la verifica
with Signature("sample.pdf") as signature:
    # Usa l'istanza della firma qui (ad es., sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento fornito tramite percorso file, opzioni di caricamento e impostazioni di firma.

Per saperne di più:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Percorso file assoluto o relativo. |
| load_options | `LoadOptions` | Le opzioni di caricamento del documento. |
| settings | `SignatureSettings` | Le impostazioni della firma. |

### Esempio

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # eseguire operazioni di firma, verifica o ricerca
    pass
```

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
