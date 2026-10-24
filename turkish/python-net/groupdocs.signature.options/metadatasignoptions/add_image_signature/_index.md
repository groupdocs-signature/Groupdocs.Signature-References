---
title: "add_image_signature yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Verilen argümanlarla yeni bir ImageMetadataSignature oluşturur ve koleksiyona ekler."
type: docs
url: /tr/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

Verilen argümanlarla yeni bir ImageMetadataSignature oluşturur ve koleksiyona ekler.

```python
def add_image_signature(self, id, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| id | `System.UInt16` | Görüntü Metadata Signature adı için benzersiz tanımlayıcı. Olası kimlik değerleri için Exif etiket spesifikasyonlarına bakınız. |
| value | `Any` | Metadata değeri. |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### Ayrıca Bakınız
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
