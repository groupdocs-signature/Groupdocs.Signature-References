---
title: "طريقة custom_sign_hash"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يوقع التجزئة المعطاة باستخدام تنفيذ توقيع مخصص."
type: docs
url: /ar/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

يوقع التجزئة المعطاة باستخدام تنفيذ توقيع مخصص.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signable_hash | `list[int]` | قيمة التجزئة التي سيتم توقيعها. |
| hash_algorithm | `HashAlgorithm` | خوارزمية التجزئة المستخدمة لإنشاء التجزئة. |
| signature_context | `SignatureContext` | السياق الذي يوفر خيارات إضافية متعلقة بالتوقيع. |

**Returns:** bytes: The signed hash as bytes.

### انظر أيضًا
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
