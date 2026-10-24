---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza un'istanza di DigitalVerifyOptions con i valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza un'istanza di DigitalVerifyOptions con i valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

Inizializza un'istanza di DigitalVerifyOptions con il percorso del file del certificato digitale fornito.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_file_path | `str` | Percorso file del certificato digitale. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Inizializza un'istanza di DigitalVerifyOptions con lo stream del certificato fornito.

```python
def __init__(self, certificate_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Stream del certificato. |

### Vedi anche
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
