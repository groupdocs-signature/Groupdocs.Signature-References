---
title: "método verify"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Verifica las firmas del documento con los datos de VerifyOptions proporcionados."
type: docs
url: /es/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Verifica las firmas del documento con los datos de VerifyOptions proporcionados.

Más información sobre la verificación de documentos firmados electrónicamente usando GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Las opciones de verificación de la firma. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Ejemplo

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

Verifica las firmas del documento usando las opciones de verificación proporcionadas y filtra los resultados según el predicado especificado.

Aprende más

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Las opciones de verificación de la firma. |
| predicate | `Func[BaseSignature, bool]` | El predicado de filtro para determinar qué firmas deben verificarse. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Ejemplo

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

Verifica las firmas del documento con una lista de datos de VerifyOptions.

Más información sobre la verificación de documentos firmados electrónicamente usando GroupDocs.Signature: [Cómo verificar que un documento está firmado electrónicamente en C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | La colección de opciones de verificación de la firma. Instancia de `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Ejemplo

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

Verifica las firmas de documentos usando las opciones de verificación proporcionadas y filtra los resultados con el predicado dado.

El método primero busca firmas que coincidan con las opciones de verificación, las filtra usando el predicado y luego verifica solo esas firmas filtradas.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | La colección de opciones de verificación de la firma. |
| predicate | `Func[BaseSignature, bool]` | El predicado de filtro para determinar qué firmas deben verificarse. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Ejemplo

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

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
