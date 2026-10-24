---
title: "verify-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Verifierar dokumentets signaturer med angivna VerifyOptions-data."
type: docs
url: /sv/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Verifierar dokumentets signaturer med angivna VerifyOptions-data.

Mer om verifiering av elektroniskt signerade dokument med GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Alternativen för signaturverifiering. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Exempel

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

Verifierar dokumentets signaturer med de tillhandahållna verifieringsalternativen och filtrerar resultaten baserat på det angivna predikatet.

Läs mer

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Alternativen för signaturverifiering. |
| predicate | `Func[BaseSignature, bool]` | Filterpredikatet för att bestämma vilka signaturer som ska verifieras. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Exempel

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

Verifierar dokumentets signaturer med en lista av VerifyOptions-data.

Mer om verifiering av elektroniskt signerade dokument med GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Samlingen med signaturverifieringsalternativ. Instans av `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Exempel

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

Verifierar dokumentets signaturer med de tillhandahållna verifieringsalternativen och filtrerar resultaten med det givna predikatet.

Metoden söker först efter signaturer som matchar verifieringsalternativen, filtrerar dem med predikatet och verifierar sedan endast de filtrerade signaturerna.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Samlingen med signaturverifieringsalternativ. |
| predicate | `Func[BaseSignature, bool]` | Filterpredikatet för att bestämma vilka signaturer som ska verifieras. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Exempel

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

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
