---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de TextVerifyOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de TextVerifyOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## __init__ {#text}

Initialise une nouvelle instance de TextVerifyOptions avec le texte de vérification.

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte à vérifier. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

Initialise une nouvelle instance de TextVerifyOptions avec le texte à vérifier et le type d'implémentation de la signature.

```python
def __init__(self, text, implementation):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte à vérifier. |
| implementation | `TextSignatureImplementation` | Type d'implémentation de la signature. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### Voir aussi
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
