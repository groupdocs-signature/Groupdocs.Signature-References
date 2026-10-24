---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una instancia de DigitalVerifyOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una instancia de DigitalVerifyOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

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

Inicializa una instancia de DigitalVerifyOptions con la ruta de archivo del certificado digital proporcionada.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_file_path | `str` | Ruta del archivo al certificado digital. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Inicializa una instancia de DigitalVerifyOptions con el flujo del certificado proporcionado.

```python
def __init__(self, certificate_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flujo del certificado. |

### Ver también
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
