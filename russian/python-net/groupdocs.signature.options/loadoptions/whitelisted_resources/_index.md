---
title: "Свойство whitelisted_resources"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Список фрагментов адресов внешних ресурсов, которые загружаются даже когда LoadOptions.SkipExternalResources установлено в true."
type: docs
url: /ru/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

Список фрагментов адресов внешних ресурсов, которые загружаются даже когда [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) установлен в true. Значение по умолчанию — пустой список.

Ресурс загружается, когда его полный адрес содержит один из фрагментов. Сравнение игнорирует регистр, пустые фрагменты игнорируются. Предпочтительно использовать длинные фрагменты, такие как `\"https://cdn.example.com/images/\"`: короткий фрагмент также может совпадать с другими адресами, содержащими его.

Установка этого свойства в `None` очищает список. Список не оказывает влияния, когда [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) равно false, поскольку в этом случае загружаются все внешние ресурсы.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### См. также
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
