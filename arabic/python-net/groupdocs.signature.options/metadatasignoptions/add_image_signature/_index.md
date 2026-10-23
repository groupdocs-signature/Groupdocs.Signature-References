---
title: "طريقة add_image_signature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ ImageMetadataSignature جديدًا بالمعلمات المحددة ويضيفه إلى المجموعة."
type: docs
url: /ar/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

ينشئ ImageMetadataSignature جديدًا بالمعلمات المحددة ويضيفه إلى المجموعة.

```python
def add_image_signature(self, id, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| id | `System.UInt16` | معرّف فريد لاسم توقيع البيانات الوصفية للصورة. راجع المراجع لمواصفات وسوم Exif للحصول على قيم معرف محتملة. |
| value | `Any` | قيمة البيانات الوصفية. |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### انظر أيضًا
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
