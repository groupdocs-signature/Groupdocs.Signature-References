---
title: "load_external_resources özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belgenin dış kaynakları yükleyip yüklemeyeceğini belirleyen bayrak."
type: docs
url: /tr/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Belgenin harici kaynakları yükleyip yüklemeyeceğini belirleyen bayrak. Bu özellik artık kullanılmamaktadır; bunun yerine ters anlam taşıyan [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) kullanın.

LoadExternalResources = True, `SkipExternalResources` = False ile eşdeğerdir ve LoadExternalResources = False, `SkipExternalResources` = True ile eşdeğerdir. Varsayılan değer False'tur, bu da dış kaynakların açıkça izin verilmedikçe yüklenmeyeceği anlamına gelir.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Ayrıca Bakınız
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
