---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Initialisiert eine neue DigitalSignOptions-Instanz mit einer Zertifikatsdatei.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_file_path | `str` | Pfad zur digitalen Zertifikatdatei. |

### Beispiel

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

Initialisiert eine neue DigitalSignOptions-Instanz mit einem Zertifikats-Stream.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digitaler Zertifikats‑Stream. |

### Beispiel

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

Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einer Erscheinungsbild-Bilddatei.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_file_path | `str` | Pfad zur digitalen Zertifikatdatei. |
| image_file_path | `str` | Dateipfad des Signatur‑Darstellungs‑Bildes. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Übergeben Sie das Zertifikat und das Erscheinungsbild‑Bild an den Konstruktor
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Initialisiert eine neue Instanz von DigitalSignOptions mit einer Zertifikatsdatei und einem Erscheinungsbild-Image-Stream.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_file_path | `str` | Pfad zur digitalen Zertifikatdatei. |
| appearence_image_stream | `io.RawIOBase` | Stream des Signatur‑Darstellungs‑Bildes. |

### Beispiel

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

Initialisiert eine neue Instanz von DigitalSignOptions mit einem Zertifikats-Stream und einer Erscheinungsbild-Bilddatei.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Digitaler Zertifikats‑Stream. |
| image_file_path | `str` | str. Dateipfad des Signatur‑Darstellungs‑Bildes. |

## __init__ {#certificate_stream-appearence_image_stream}

Initialisiert eine neue DigitalSignOptions-Instanz mit einem Zertifikats-Stream und einem Erscheinungsbild-Image-Stream.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digitaler Zertifikats‑Stream. |
| appearence_image_stream | `io.RawIOBase` | Stream des Signatur‑Darstellungs‑Bildes. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Zertifikat und Darstellungs‑Bild aus Streams laden
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Siehe auch
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
