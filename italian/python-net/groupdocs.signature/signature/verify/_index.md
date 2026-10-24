---
title: "metodo verify"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Verifica le firme del documento con i dati VerifyOptions forniti."
type: docs
url: /it/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Verifica le firme del documento con i dati VerifyOptions forniti.

Maggiori informazioni sulla verifica dei documenti firmati elettronicamente usando GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Le opzioni di verifica della firma. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Esempio

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

Verifica le firme del documento utilizzando le opzioni di verifica fornite e filtra i risultati in base al predicato specificato.

Maggiori informazioni

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Le opzioni di verifica della firma. |
| predicate | `Func[BaseSignature, bool]` | Il predicato di filtro per determinare quali firme devono essere verificate. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Esempio

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

Verifica le firme del documento con un elenco di dati VerifyOptions.

Maggiori informazioni sulla verifica dei documenti firmati elettronicamente usando GroupDocs.Signature: [Come verificare che un documento sia firmato elettronicamente in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | La raccolta delle opzioni di verifica della firma. Istanza di `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Esempio

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

Verifica le firme dei documenti utilizzando le opzioni di verifica fornite e filtra i risultati con il predicato specificato.

Il metodo prima ricerca le firme che corrispondono alle opzioni di verifica, le filtra usando il predicato e poi verifica solo le firme filtrate.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | La raccolta delle opzioni di verifica della firma. |
| predicate | `Func[BaseSignature, bool]` | Il predicato di filtro per determinare quali firme devono essere verificate. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Esempio

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

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
