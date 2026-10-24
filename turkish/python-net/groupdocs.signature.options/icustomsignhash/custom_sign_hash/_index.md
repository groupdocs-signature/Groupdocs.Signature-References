---
title: "custom_sign_hash yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Verilen hash'i özel bir imzalama uygulaması kullanarak imzalar."
type: docs
url: /tr/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Verilen hash'i özel bir imzalama uygulaması kullanarak imzalar.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signable_hash | `list[int]` | İmzalanacak hash değeri. |
| hash_algorithm | `HashAlgorithm` | Hash'i oluşturmak için kullanılan hash algoritması. |
| signature_context | `SignatureContext` | Ek imza ile ilgili seçenekler sağlayan bağlam. |

**Returns:** bytes: The signed hash as bytes.

### Ayrıca Bakınız
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
