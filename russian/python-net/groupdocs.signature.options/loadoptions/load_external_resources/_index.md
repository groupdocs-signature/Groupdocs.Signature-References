---
title: "Свойство load_external_resources"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, определяющий, загружает ли документ внешние ресурсы."
type: docs
url: /ru/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Флаг, определяющий, загружает ли документ внешние ресурсы. Это свойство устарело; вместо него используйте [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), которое имеет противоположное значение.

LoadExternalResources = True эквивалентно `SkipExternalResources` = False, а LoadExternalResources = False эквивалентно `SkipExternalResources` = True. Значение по умолчанию — False, что означает, что внешние ресурсы не загружаются, если явно не разрешено.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### См. также
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
