---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatbestand."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatbestand.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_file_path | `str` | Pad naar digitaal certificaatbestand. |
| password | `str` | Wachtwoord voor digitaal certificaat. |

### Voorbeeld

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Maak een DigitalVBA-extensie met behulp van een certificaatbestand en wachtwoord.
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatstroom.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase met het digitale certificaat. |
| password | `str` | str-wachtwoord voor het digitale certificaat. |

### Zie ook
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
