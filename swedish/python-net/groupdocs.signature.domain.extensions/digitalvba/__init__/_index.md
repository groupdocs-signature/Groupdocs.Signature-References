---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av DigitalVBA-klassen med en certifikatfil."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Initierar en ny instans av DigitalVBA-klassen med en certifikatfil.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_file_path | `str` | Digitalt certifikatfilens sökväg. |
| password | `str` | Lösenord för digitalt certifikat. |

### Exempel

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Skapa en DigitalVBA-utökning med en certifikatfil och lösenord
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Initierar en ny instans av DigitalVBA-klassen med en certifikatström.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase som innehåller det digitala certifikatet. |
| password | `str` | str-lösenord för det digitala certifikatet. |

### Se även
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
