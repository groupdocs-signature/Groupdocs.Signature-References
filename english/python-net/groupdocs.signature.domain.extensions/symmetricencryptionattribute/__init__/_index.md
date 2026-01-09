---
title: SymmetricEncryptionAttribute constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---

## __init__ {#groupdocs.signature.domain.extensions.SymmetricAlgorithmType-System.String}

Creates symmetric algorithm with parameters and default passphrase.



```python
def __init__(self, algorithm_type, key):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| algorithm_type | groupdocs.signature.domain.extensions.SymmetricAlgorithmType | Encryption algorithm type |
| key | System.String | Encryption key |


## __init__ {#groupdocs.signature.domain.extensions.SymmetricAlgorithmType-System.String-System.String}

Creates symmetric algorithm with parameters.



```python
def __init__(self, algorithm_type, key, salt):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| algorithm_type | groupdocs.signature.domain.extensions.SymmetricAlgorithmType | Specify symmetric algorithm type |
| key | System.String | Encryption key |
| salt | System.String | Passphrase for encryption |



### See Also
* module [`groupdocs.signature.domain.extensions`](../../)
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute)
