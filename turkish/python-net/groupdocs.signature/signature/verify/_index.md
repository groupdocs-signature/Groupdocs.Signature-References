---
title: "verify yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge imzalarını verilen VerifyOptions verileriyle doğrular."
type: docs
url: /tr/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Belge imzalarını verilen VerifyOptions verileriyle doğrular.

GroupDocs.Signature kullanarak elektronik imzalı belgelerin doğrulanması hakkında daha fazla bilgi:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| verify_options | `VerifyOptions` | İmza doğrulama seçenekleri. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Örnek

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

Belge imzalarını sağlanan doğrulama seçeneklerini kullanarak doğrular ve sonuçları belirtilen koşula göre filtreler.

Daha fazla bilgi edinin

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| verify_options | `VerifyOptions` | İmza doğrulama seçenekleri. |
| predicate | `Func[BaseSignature, bool]` | Hangi imzaların doğrulanacağını belirlemek için filtre önermesi. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Örnek

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

Belge imzalarını bir VerifyOptions listesiyle doğrular.

GroupDocs.Signature kullanarak elektronik imzalı belgelerin doğrulanması hakkında daha fazla bilgi: [C#'ta belgenin elektronik olarak imzalı olduğunu nasıl doğrularsınız](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | İmza doğrulama seçenekleri koleksiyonu. `GroupDocs.Signature.Options.VerifyOptionsCollection` örneği. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Örnek

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

Sağlanan doğrulama seçeneklerini kullanarak belge imzalarını doğrular ve verilen koşula göre sonuçları filtreler.

Yöntem önce doğrulama seçenekleriyle eşleşen imzaları arar, önermeyi kullanarak filtreler ve ardından yalnızca bu filtrelenmiş imzaları doğrular.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | İmza doğrulama seçenekleri koleksiyonu. |
| predicate | `Func[BaseSignature, bool]` | Hangi imzaların doğrulanacağını belirlemek için filtre önermesi. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Örnek

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

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
