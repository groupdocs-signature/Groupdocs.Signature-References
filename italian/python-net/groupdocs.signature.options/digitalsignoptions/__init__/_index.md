---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe DigitalSignOptions con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe DigitalSignOptions con valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Inizializza una nuova istanza di DigitalSignOptions con un file di certificato.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_file_path | `str` | Percorso del file del certificato digitale. |

### Esempio

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

Inizializza una nuova istanza di DigitalSignOptions con un flusso di certificato.

```python
def __init__(self, certificate_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flusso del certificato digitale. |

### Esempio

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

Inizializza una nuova istanza della classe DigitalSignOptions con un file di certificato e un file immagine di aspetto.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_file_path | `str` | Percorso del file del certificato digitale. |
| image_file_path | `str` | Percorso file dell'immagine di aspetto della firma. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Passa il certificato e l'immagine di aspetto al costruttore
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Inizializza una nuova istanza di DigitalSignOptions con un file di certificato e un flusso immagine di aspetto.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_file_path | `str` | Percorso del file del certificato digitale. |
| appearence_image_stream | `io.RawIOBase` | Flusso dell'immagine di aspetto della firma. |

### Esempio

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

Inizializza una nuova istanza di DigitalSignOptions con un flusso di certificato e un file immagine di aspetto.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Flusso del certificato digitale. |
| image_file_path | `str` | str. Percorso file dell'immagine di aspetto della firma. |

## __init__ {#certificate_stream-appearence_image_stream}

Inizializza una nuova istanza di DigitalSignOptions con un flusso di certificato e un flusso immagine di aspetto.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Flusso del certificato digitale. |
| appearence_image_stream | `io.RawIOBase` | Flusso dell'immagine di aspetto della firma. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Carica certificato e immagine di aspetto dai flussi
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Vedi anche
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
