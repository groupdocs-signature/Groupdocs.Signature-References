---
title: "méthode verify"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Vérifie les signatures du document avec les données VerifyOptions fournies."
type: docs
url: /fr/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Vérifie les signatures du document avec les données VerifyOptions fournies.

Plus d'informations sur la vérification de documents signés électroniquement à l'aide de GroupDocs.Signature :
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Les options de vérification de la signature. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

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

## verify {#verify_options-predicate}

Vérifie les signatures du document en utilisant les options de vérification fournies et filtre les résultats selon le prédicat spécifié.

En savoir plus

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Les options de vérification de la signature. |
| predicate | `Func[BaseSignature, bool]` | Le prédicat de filtrage pour déterminer quelles signatures doivent être vérifiées. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Exemple

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

Vérifie les signatures du document avec une liste de données VerifyOptions.

Plus d'informations sur la vérification de documents signés électroniquement à l'aide de GroupDocs.Signature : [Comment vérifier qu'un document est signé électroniquement en C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | La collection des options de vérification de la signature. Instance de `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

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

## verify {#verify_options_list-predicate}

Vérifie les signatures de documents en utilisant les options de vérification fournies et filtre les résultats avec le prédicat donné.

La méthode recherche d'abord les signatures correspondant aux options de vérification, les filtre à l'aide du prédicat, puis ne vérifie que les signatures filtrées.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | La collection des options de vérification de la signature. |
| predicate | `Func[BaseSignature, bool]` | Le prédicat de filtrage pour déterminer quelles signatures doivent être vérifiées. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Exemple

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

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
