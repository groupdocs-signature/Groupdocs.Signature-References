---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

Initialiseert een nieuw exemplaar van TextVerifyOptions met verificatietekst.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Tekst om te verifiëren. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

Initialiseert een nieuw TextVerifyOptions-exemplaar met de te verifiëren tekst en het type handtekeningimplementatie.

```python
def __init__(self, text, implementation):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Tekst om te verifiëren. |
| implementation | `TextSignatureImplementation` | Handtekeningimplementatietype. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### Zie ook
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
