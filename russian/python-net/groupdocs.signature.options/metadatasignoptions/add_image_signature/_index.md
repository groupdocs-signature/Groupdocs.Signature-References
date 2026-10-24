---
title: "Метод add_image_signature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Создаёт новый ImageMetadataSignature с заданными аргументами и добавляет его в коллекцию."
type: docs
url: /ru/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

Создаёт новый ImageMetadataSignature с заданными аргументами и добавляет его в коллекцию.

```python
def add_image_signature(self, id, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| id | `System.UInt16` | Уникальный идентификатор имени подписи Image Metadata. См. ссылки на спецификации тегов Exif для возможных значений id. |
| value | `Any` | Значение метаданных. |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### См. также
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
