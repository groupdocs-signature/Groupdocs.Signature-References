---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av DigitalSignOptions-klassen med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av DigitalSignOptions-klassen med standardvärden.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Initierar en ny DigitalSignOptions-instans med en certifikatfil.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_file_path | `str` | Digitalt certifikatfilens sökväg. |

### Exempel

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

Initierar en ny DigitalSignOptions-instans med ett certifikatflöde.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digitalt certifikat‑ström. |

### Exempel

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

Initierar en ny instans av DigitalSignOptions-klassen med en certifikatfil och en bildfil för utseende.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_file_path | `str` | Digitalt certifikatfilens sökväg. |
| image_file_path | `str` | Sökväg till bildfil för signaturens utseende. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Skicka certifikatet och bild för utseende till konstruktorn
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Initierar en ny instans av DigitalSignOptions med en certifikatfil och ett bildflöde för utseende.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_file_path | `str` | Digitalt certifikatfilens sökväg. |
| appearence_image_stream | `io.RawIOBase` | Ström för bild av signaturens utseende. |

### Exempel

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

Initierar en ny instans av DigitalSignOptions med ett certifikatflöde och en bildfil för utseende.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Digitalt certifikat‑ström. |
| image_file_path | `str` | str. Sökväg till bildfil för signaturens utseende. |

## __init__ {#certificate_stream-appearence_image_stream}

Initierar en ny DigitalSignOptions-instans med ett certifikatflöde och ett bildflöde för utseende.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digitalt certifikat‑ström. |
| appearence_image_stream | `io.RawIOBase` | Ström för bild av signaturens utseende. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Läs in certifikat och bild för utseende från strömmar
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Se även
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
