---
title: "TextFormFieldSignature sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "PDF belgeleri için metin giriş form alanı imza özelliklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

PDF belgeleri için metin giriş form alanı imza özelliklerini temsil eder.

TextFormFieldSignature türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | Önceden tanımlı bir adla PdfTextFormFieldSignature başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | Önceden tanımlı bir adla PdfTextFormFieldSignature başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | FormField Signature örneğini kopyalar. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | Bu imzayı, tür ve özellik değerlerine göre eşitlik açısından başka bir imza ile karşılaştırır. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | GetHashCode metodunu geçersiz kılar. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | Form alanı girişinin metni. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | İmza oluşturma tarihi. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bu imzanın belgeden silinip silinmediğini gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | İmzanın yüksekliği. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bu bileşenin bir imza (`True`) mı yoksa belge içeriği (`False`) mı olduğunu gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | İmzanın sol konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | İmzanın değiştirilme tarihi. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | Benzersiz form alanı adı. ([`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/) üzerinden devralınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | İmzanın bulunduğu sayfa numarası. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | İmzanın benzersiz tanımlayıcısı, güncelleme veya silme işlemleriyle belgede imzayı değiştirmek için kullanılır. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | İmza türü. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | İmzanın üst konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | Form alanı türü. ([`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/) üzerinden devralınmıştır) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | Form alanı veri nesnesi. ([`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/) üzerinden devralınmıştır) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | İmzanın genişliği. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # "FieldText" adında bir metin form alanı oluştur ve "Value1" değerini ata
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # Bunun için form alanı seçenekleri oluştur
        options = FormFieldSignOptions(text_field)

        # Form alanının konumunu ve boyutunu ayarla
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # Belgeyi imzalayın ve sonucu kaydedin
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
