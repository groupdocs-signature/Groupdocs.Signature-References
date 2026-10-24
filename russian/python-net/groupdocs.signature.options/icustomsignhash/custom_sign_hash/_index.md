---
title: "метод custom_sign_hash."
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Подписывает заданный хеш с использованием пользовательской реализации подписи."
type: docs
url: /ru/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Подписывает заданный хеш с использованием пользовательской реализации подписи.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signable_hash | `list[int]` | Хеш-значение, которое будет подписано. |
| hash_algorithm | `HashAlgorithm` | Алгоритм хеширования, используемый для создания хеша. |
| signature_context | `SignatureContext` | Контекст, предоставляющий дополнительные параметры, связанные с подписью. |

**Returns:** bytes: The signed hash as bytes.

### См. также
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
