---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe DigitalSignOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe DigitalSignOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Initialise une nouvelle instance de DigitalSignOptions avec un fichier de certificat.

```python
def __init__(self, certificate_file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Chemin du fichier de certificat numérique. |

### Exemple

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

Initialise une nouvelle instance de DigitalSignOptions avec un flux de certificat.

```python
def __init__(self, certificate_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flux de certificat numérique. |

### Exemple

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

Initialise une nouvelle instance de la classe DigitalSignOptions avec un fichier de certificat et un fichier d'image d'apparence.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Chemin du fichier de certificat numérique. |
| image_file_path | `str` | Chemin du fichier d'image d'apparence de la signature. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Passez le certificat et l'image d'apparence au constructeur
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Initialise une nouvelle instance de DigitalSignOptions avec un fichier de certificat et un flux d'image d'apparence.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Chemin du fichier de certificat numérique. |
| appearence_image_stream | `io.RawIOBase` | Flux d'image d'apparence de la signature. |

### Exemple

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

Initialise une nouvelle instance de DigitalSignOptions avec un flux de certificat et un fichier d'image d'apparence.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Flux de certificat numérique. |
| image_file_path | `str` | str. Chemin du fichier d'image d'apparence de la signature. |

## __init__ {#certificate_stream-appearence_image_stream}

Initialise une nouvelle instance de DigitalSignOptions avec un flux de certificat et un flux d'image d'apparence.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flux de certificat numérique. |
| appearence_image_stream | `io.RawIOBase` | Flux d'image d'apparence de la signature. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Charger le certificat et l'image d'apparence depuis les flux
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Voir aussi
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
