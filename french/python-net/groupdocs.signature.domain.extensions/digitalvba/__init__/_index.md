---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe DigitalVBA avec un fichier de certificat."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Initialise une nouvelle instance de la classe DigitalVBA avec un fichier de certificat.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Chemin du fichier de certificat numérique. |
| password | `str` | Mot de passe du certificat numérique. |

### Exemple

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Créer une extension DigitalVBA en utilisant un fichier de certificat et un mot de passe
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Initialise une nouvelle instance de la classe DigitalVBA avec un flux de certificat.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase contenant le certificat numérique. |
| password | `str` | str mot de passe pour le certificat numérique. |

### Voir aussi
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
