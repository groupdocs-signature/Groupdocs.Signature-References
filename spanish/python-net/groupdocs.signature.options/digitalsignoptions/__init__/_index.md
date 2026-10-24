---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase DigitalSignOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase DigitalSignOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Inicializa una nueva instancia de DigitalSignOptions con un archivo de certificado.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_file_path | `str` | Ruta del archivo del certificado digital. |

### Ejemplo

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

Inicializa una nueva instancia de DigitalSignOptions con un flujo de certificado.

```python
def __init__(self, certificate_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flujo de certificado digital. |

### Ejemplo

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

Inicializa una nueva instancia de la clase DigitalSignOptions con un archivo de certificado y un archivo de imagen de apariencia.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_file_path | `str` | Ruta del archivo del certificado digital. |
| image_file_path | `str` | Ruta del archivo de imagen de apariencia de la firma. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Pase el certificado y la imagen de apariencia al constructor
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Inicializa una nueva instancia de DigitalSignOptions con un archivo de certificado y un flujo de imagen de apariencia.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_file_path | `str` | Ruta del archivo del certificado digital. |
| appearence_image_stream | `io.RawIOBase` | Flujo de imagen de apariencia de la firma. |

### Ejemplo

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

Inicializa una nueva instancia de DigitalSignOptions con un flujo de certificado y un archivo de imagen de apariencia.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Flujo de certificado digital. |
| image_file_path | `str` | str. Ruta del archivo de imagen de apariencia de la firma. |

## __init__ {#certificate_stream-appearence_image_stream}

Inicializa una nueva instancia de DigitalSignOptions con un flujo de certificado y un flujo de imagen de apariencia.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flujo de certificado digital. |
| appearence_image_stream | `io.RawIOBase` | Flujo de imagen de apariencia de la firma. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Cargar certificado e imagen de apariencia desde flujos
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Ver también
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
