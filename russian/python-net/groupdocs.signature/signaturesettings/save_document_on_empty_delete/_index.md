---
title: "save_document_on_empty_delete свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, определяющий, будет ли исходный документ пересохранён, когда метод Delete не имеет затронутых подписей для удаления."
type: docs
url: /ru/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Флаг, определяющий, будет ли исходный документ пересохранён, когда метод Delete не имеет затронутых подписей для удаления.

Когда True (по умолчанию), документ сохраняется с журналом истории (дата и тип операции), даже если подписи не были удалены; когда False, исходный документ остаётся без изменений.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### См. также
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
