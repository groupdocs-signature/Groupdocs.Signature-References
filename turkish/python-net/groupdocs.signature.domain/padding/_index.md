---
title: "Padding sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Elemanla ilişkili dolgu veya kenar boşluğu bilgisini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Elemanla ilişkili dolgu veya kenar boşluğu bilgisini temsil eder.

Padding türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Padding sınıfının yeni bir örneğini sıfır değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Padding sınıfının yeni bir örneğini tüm kenarlar için sağlanan dolgu boyutunu kullanarak başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Padding sınıfının yeni bir örneğini sağlanan dolgu boyutlarını kullanarak başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Bu nesnenin bir kopyasını alır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | Tüm kenarlar için dolgu değeri. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | Alt kenar için dolgu değeri. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Sağ ve sol kenarlar için birleşik dolgu. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | Sol kenar için dolgu değeri. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | Sağ kenar için dolgu değeri. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | Üst kenar için dolgu değeri. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Üst ve alt kenarlar için birleşik dolgu. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Hiç dolgu içermeyen bir Padding nesnesi sağlar. |

### Örnek

```python
from groupdocs.signature.domain import Padding

# Tüm kenarlarda 5 birimlik eşit dolgu
uniform = Padding(5)

# Sağ ve alt tarafta belirli dolgu
custom = Padding(right=40, bottom=60)
```

### Guides
`Padding` kullanan görev kılavuzları:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
