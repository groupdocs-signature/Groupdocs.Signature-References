---
title: "properti load_external_resources"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Bendera yang menentukan apakah dokumen memuat sumber daya eksternal."
type: docs
url: /id/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

Bendera yang menentukan apakah dokumen memuat sumber daya eksternal. Properti ini sudah usang; gunakan [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) sebagai gantinya, yang memiliki arti sebaliknya.

LoadExternalResources = True setara dengan `SkipExternalResources` = False, dan LoadExternalResources = False setara dengan `SkipExternalResources` = True. Nilai defaultnya adalah False, yang berarti sumber daya eksternal tidak dimuat kecuali secara eksplisit diizinkan.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### Lihat Juga
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
