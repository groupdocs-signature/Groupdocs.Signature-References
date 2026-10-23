---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einer Zertifikatsdatei."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einer Zertifikatsdatei.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_file_path | `str` | Pfad zur digitalen Zertifikatdatei. |
| password | `str` | Passwort für das digitale Zertifikat. |

### Beispiel

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Erstelle eine DigitalVBA-Erweiterung mit einer Zertifikatdatei und einem Passwort
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einem Zertifikat-Stream.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase, das das digitale Zertifikat enthält. |
| password | `str` | str Passwort für das digitale Zertifikat. |

### Siehe auch
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
