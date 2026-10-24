---
title: "метод clone"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Клонировать экземпляр подписи метаданных."
type: docs
url: /ru/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Клонировать экземпляр подписи метаданных.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Пример

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Создать копию стандартной подписи метаданных с новым значением
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Клонирует экземпляр подписи метаданных PDF с заданным значением.

```python
def clone(self, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | `Any` | Значение для нового клонированного объекта. |

**Returns:** A cloned metadata signature instance.

### Пример

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Клонировать существующую подпись метаданных с новым значением
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### См. также
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
