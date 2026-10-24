---
title: "verify-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Verifieert de handtekeningen van het document met de opgegeven VerifyOptions-gegevens."
type: docs
url: /nl/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Verifieert de handtekeningen van het document met de opgegeven VerifyOptions-gegevens.

Meer over verificatie van elektronisch ondertekende documenten met GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| verify_options | `VerifyOptions` | De verificatie‑opties voor handtekeningen. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

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

## verify {#verify_options-predicate}

Verifieert de handtekeningen van het document met de opgegeven verificatieopties en filtert de resultaten op basis van het gespecificeerde predicaat.

Meer informatie

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| verify_options | `VerifyOptions` | De verificatie‑opties voor handtekeningen. |
| predicate | `Func[BaseSignature, bool]` | De filter‑predicate om te bepalen welke handtekeningen moeten worden geverifieerd. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options, lambda s: True)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list}

Verifieert de handtekeningen van het document met een lijst van VerifyOptions-gegevens.

Meer over verificatie van elektronisch ondertekende documenten met GroupDocs.Signature: [Hoe een document elektronisch te verifiëren in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | De collectie van verificatie‑opties voor handtekeningen. Een instantie van `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

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

## verify {#verify_options_list-predicate}

Verifieert documenthandtekeningen met behulp van de opgegeven verificatieopties en filtert de resultaten met de gegeven predicaat.

De methode zoekt eerst naar handtekeningen die overeenkomen met de verificatie‑opties, filtert ze met de predicate, en verifieert vervolgens alleen die gefilterde handtekeningen.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | De collectie van verificatie‑opties voor handtekeningen. |
| predicate | `Func[BaseSignature, bool]` | De filter‑predicate om te bepalen welke handtekeningen moeten worden geverifieerd. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify([options], lambda s: s.text == "John Smith")
        print(f"Document is signed by John Smith: {result[0].is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
