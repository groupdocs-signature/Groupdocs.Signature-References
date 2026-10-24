---
title: "TextSignature sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "TextSignature sınıfı, metin imza özelliklerini içerir."
type: docs
url: /tr/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

TextSignature sınıfı, metin imza özelliklerini içerir.

TextSignature türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | İmza veya arama işlemiyle elde edilen benzersiz imza tanımlayıcısıyla bir TextSignature nesnesi başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Text Signature örneğini klonlar. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Belirtilen imzayı bu örnekle eşitlik açısından karşılaştırır. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | İmza için hash kodunu döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | İmzanın belgeye özgü olup olmadığını gösteren yerel özellik. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | Metin imza uygulaması. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | İmzanın metni. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | İmza oluşturma tarihi. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bu imzanın belgeden silinip silinmediğini gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | İmzanın yüksekliği. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bu bileşenin bir imza (`True`) mı yoksa belge içeriği (`False`) mı olduğunu gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | İmzanın sol konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | İmzanın değiştirilme tarihi. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | İmzanın bulunduğu sayfa numarası. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | İmzanın benzersiz tanımlayıcısı, güncelleme veya silme işlemleriyle belgede imzayı değiştirmek için kullanılır. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | İmza türü. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | İmzanın üst konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | İmzanın genişliği. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
