---
title: "save_document_on_empty_update свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, определяющий, будет ли исходный документ пересохранён, когда метод Update не имеет подписей для обновления."
type: docs
url: /ru/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

Флаг, определяющий, будет ли исходный документ пересохранён, когда метод `Update` не имеет подписей для обновления.

Если установить `True` (по умолчанию), документ сохраняется с соответствующим журналом процесса истории (дата и тип операции), даже если подписи не обновляются. При установке `False` исходный документ не изменяется вовсе.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### См. также
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
