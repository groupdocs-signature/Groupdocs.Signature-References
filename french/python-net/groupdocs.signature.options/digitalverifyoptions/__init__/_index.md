---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une instance DigitalVerifyOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une instance DigitalVerifyOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

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

Initialise une instance DigitalVerifyOptions avec le chemin de fichier du certificat numérique fourni.

```python
def __init__(self, certificate_file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Chemin du fichier vers le certificat numérique. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Initialise une instance DigitalVerifyOptions avec le flux du certificat fourni.

```python
def __init__(self, certificate_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flux du certificat. |

### Voir aussi
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
