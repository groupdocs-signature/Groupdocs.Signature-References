---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine DigitalVerifyOptions‑Instanz mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine DigitalVerifyOptions‑Instanz mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

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

Initialisiert eine DigitalVerifyOptions‑Instanz mit dem angegebenen Dateipfad des digitalen Zertifikats.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_file_path | `str` | Dateipfad zum digitalen Zertifikat. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Initialisiert eine DigitalVerifyOptions‑Instanz mit dem angegebenen Zertifikat‑Stream.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Stream des Zertifikats. |

### Siehe auch
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
