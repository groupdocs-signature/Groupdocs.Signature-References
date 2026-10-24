---
title: "return_content свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, определяющий, возвращается ли изображение QR‑Code для каждой подписи на странице документа."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/
is_root: false
weight: 2040
---


## return_content property

Флаг, определяющий, возвращается ли изображение QR‑Code для каждой подписи на странице документа. Когда установлен в True, необработанные данные изображения сохраняются в свойстве подписи `content` в формате, указанном параметром `return_content_type`. По умолчанию отключено.

### Definition:
```python
@property
def return_content(self):
    ...
@return_content.setter
def return_content(self, value):
    ...
```

### См. также
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
