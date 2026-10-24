---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase DigitalVBA con un archivo de certificado."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Inicializa una nueva instancia de la clase DigitalVBA con un archivo de certificado.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_file_path | `str` | Ruta del archivo del certificado digital. |
| password | `str` | Contraseña del certificado digital. |

### Ejemplo

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Crear una extensión DigitalVBA usando un archivo de certificado y contraseña.
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Inicializa una nueva instancia de la clase DigitalVBA con un flujo de certificado.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase que contiene el certificado digital. |
| password | `str` | str contraseña para el certificado digital. |

### Ver también
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
