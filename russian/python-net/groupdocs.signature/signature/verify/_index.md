---
title: "метод verify"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Проверяет подписи документа с использованием заданных данных VerifyOptions."
type: docs
url: /ru/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Проверяет подписи документа с использованием заданных данных VerifyOptions.

Подробнее о проверке электронных подписей документов с использованием GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Параметры проверки подписи. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Пример

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

Проверяет подписи документа, используя предоставленные параметры проверки, и фильтрует результаты на основе указанного предиката.

Узнать больше

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Параметры проверки подписи. |
| predicate | `Func[BaseSignature, bool]` | Предикат фильтра, определяющий, какие подписи следует проверять. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Пример

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

Проверяет подписи документа со списком данных VerifyOptions.

Подробнее о проверке электронных подписей документов с использованием GroupDocs.Signature: [Как проверить, что документ подписан электронно в C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Коллекция параметров проверки подписи. Экземпляр `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Пример

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

Проверяет подписи документов, используя предоставленные параметры проверки, и фильтрует результаты с помощью заданного предиката.

Метод сначала ищет подписи, соответствующие параметрам проверки, фильтрует их с помощью предиката, а затем проверяет только отфильтрованные подписи.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Коллекция параметров проверки подписи. |
| predicate | `Func[BaseSignature, bool]` | Предикат фильтра, определяющий, какие подписи следует проверять. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Пример

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

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
