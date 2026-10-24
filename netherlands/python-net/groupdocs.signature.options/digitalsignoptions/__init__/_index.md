---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Initialiseert een nieuw DigitalSignOptions-exemplaar met een certificaatbestand.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_file_path | `str` | Pad naar digitaal certificaatbestand. |

### Voorbeeld

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

Initialiseert een nieuw DigitalSignOptions-exemplaar met een certificaatstroom.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digitale certificaatstroom. |

### Voorbeeld

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

Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met een certificaatbestand en een weergave‑afbeeldingsbestand.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_file_path | `str` | Pad naar digitaal certificaatbestand. |
| image_file_path | `str` | Bestandspad van handtekeningweergave-afbeelding. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Geef het certificaat en de weergave‑afbeelding door aan de constructor
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Initialiseert een nieuw exemplaar van DigitalSignOptions met een certificaatbestand en een weergave‑afbeeldingsstroom.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_file_path | `str` | Pad naar digitaal certificaatbestand. |
| appearence_image_stream | `io.RawIOBase` | Stroom van handtekeningweergave-afbeelding. |

### Voorbeeld

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

Initialiseert een nieuw exemplaar van DigitalSignOptions met een certificaatstroom en een weergave‑afbeeldingsbestand.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Digitale certificaatstroom. |
| image_file_path | `str` | str. Bestandspad van handtekeningweergave-afbeelding. |

## __init__ {#certificate_stream-appearence_image_stream}

Initialiseert een nieuw DigitalSignOptions-exemplaar met een certificaatstroom en een weergave‑afbeeldingsstroom.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digitale certificaatstroom. |
| appearence_image_stream | `io.RawIOBase` | Stroom van handtekeningweergave-afbeelding. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Laad certificaat en weergave-afbeelding vanuit streams
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Zie ook
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
