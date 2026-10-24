---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe DigitalVBA con un file di certificato."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Inizializza una nuova istanza della classe DigitalVBA con un file di certificato.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_file_path | `str` | Percorso del file del certificato digitale. |
| password | `str` | Password del certificato digitale. |

### Esempio

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Crea un'estensione DigitalVBA usando un file di certificato e password.
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Inizializza una nuova istanza della classe DigitalVBA con un flusso di certificato.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase contenente il certificato digitale. |
| password | `str` | str password per il certificato digitale. |

### Vedi anche
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
