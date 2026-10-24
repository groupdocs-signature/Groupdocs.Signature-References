---
title: "whitelisted_resources özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "LoadOptions.SkipExternalResources true olduğunda bile yüklenen dış kaynakların adres parçacıklarının listesi."
type: docs
url: /tr/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

Harici kaynakların, [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true olduğunda bile yüklenecek adres parçacıklarının listesi. Varsayılan değer boş bir listedir.

Bir kaynağın tam adresi parçacıklardan birini içerdiğinde kaynak yüklenir. Karşılaştırma büyük/küçük harfi göz ardı eder ve boş parçacıklar yoksayılır. `\"https://cdn.example.com/images/\"` gibi uzun parçacıkları tercih edin: kısa bir parçacık da içinde bulundurduğu diğer adreslerle eşleşebilir.

Bu özelliği `None` olarak ayarlamak listeyi temizler. Liste, [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) false olduğunda etkisizdir, çünkü o zaman her dış kaynak yüklenir.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Ayrıca Bakınız
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
