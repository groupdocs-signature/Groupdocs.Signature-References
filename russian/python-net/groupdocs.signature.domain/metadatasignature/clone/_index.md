---
title: "метод clone"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Создаёт клон экземпляра подписи метаданных."
type: docs
url: /ru/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Создаёт клон экземпляра подписи метаданных.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Пример

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Создайте новую подпись metadata на основе предопределённой подписи AUTHOR
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Создать клон экземпляра подписи метаданных с заданным значением.

```python
def clone(self, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | `Any` | Значение для нового клонированного объекта. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Пример

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Клонировать существующую подпись метаданных с новым значением
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### См. также
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
