---
title: verify method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Verifies the document signatures with given VerifyOptions data."
type: docs
url: /python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Verifies the document signatures with given VerifyOptions data.

More about electronically signed documents verification using GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| verify_options | `VerifyOptions` | The signature verification options. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Example

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

Verifies the document signatures using the provided verification options and filters the results based on the specified predicate.

Learn more

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| verify_options | `VerifyOptions` | The signature verification options. |
| predicate | `Func[BaseSignature, bool]` | The filter predicate to determine which signatures should be verified. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Example

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

Verifies the document signatures with a list of VerifyOptions data.

More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | The signature verification options collection. Instance of `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Example

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

Verifies document signatures using the provided verification options and filters the results with the given predicate.

The method first searches for signatures matching the verification options, filters them using the predicate, and then verifies only those filtered signatures.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | The signature verification options collection. |
| predicate | `Func[BaseSignature, bool]` | The filter predicate to determine which signatures should be verified. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Example

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

### See Also
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
