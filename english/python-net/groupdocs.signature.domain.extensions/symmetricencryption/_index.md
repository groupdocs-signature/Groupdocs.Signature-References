---
title: SymmetricEncryption class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/symmetricencryption/
is_root: false
weight: 290
---

## SymmetricEncryption class

Implements standard symmetric algorithms for data encryption with single key and passphrase (salt).



The SymmetricEncryption type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/#groupdocs.signature.domain.extensions.SymmetricAlgorithmType-str-str) | Creates symmetric encryption algorithm with parameters. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/#groupdocs.signature.domain.extensions.SymmetricAlgorithmType-str) | Creates symmetric encryption algorithm with default passphrase |


### Properties
| Property | Description |
| :- | :- |
| [algorithm_type](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/algorithm_type) | Gets or sets type of symmetric algorithm. |
| [key](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/key) | Gets or sets key of encryption algorithm. |
| [salt](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/salt) | Gets or sets passphrase of encryption algorithm. |


### Methods
| Method | Description |
| :- | :- |
| [encode](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/encode/#str) | Encrypts string based on provided algorithm type, key and salt parameters |
| [decode](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/decode/#str) | Decrypts string based on provided algorithm type, key and salt parameters |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
