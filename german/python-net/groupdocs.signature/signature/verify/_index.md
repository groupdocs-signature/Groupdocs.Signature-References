---
title: "Methode verify"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten."
type: docs
url: /de/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten.

Mehr über die Verifizierung elektronisch signierter Dokumente mit GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Die Optionen zur Signaturverifizierung. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Beispiel

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

Überprüft die Dokumentensignaturen unter Verwendung der bereitgestellten Verifizierungsoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat.

Mehr erfahren

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Die Optionen zur Signaturverifizierung. |
| predicate | `Func[BaseSignature, bool]` | Das Filterprädikat, um zu bestimmen, welche Signaturen verifiziert werden sollen. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Beispiel

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

Überprüft die Dokumentensignaturen mit einer Liste von VerifyOptions-Daten.

Mehr über die Überprüfung elektronisch signierter Dokumente mit GroupDocs.Signature: [Wie man ein Dokument in C# elektronisch signiert überprüft](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Die Sammlung der Optionen zur Signaturüberprüfung. Instanz von `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Beispiel

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

Überprüft Dokumentensignaturen mit den bereitgestellten Verifizierungsoptionen und filtert die Ergebnisse mit dem angegebenen Prädikat.

Die Methode sucht zunächst nach Signaturen, die den Verifizierungsoptionen entsprechen, filtert sie mithilfe des Prädikats und verifiziert anschließend nur die gefilterten Signaturen.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Die Sammlung der Optionen zur Signaturüberprüfung. |
| predicate | `Func[BaseSignature, bool]` | Das Filterprädikat, um zu bestimmen, welche Signaturen verifiziert werden sollen. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Beispiel

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

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
