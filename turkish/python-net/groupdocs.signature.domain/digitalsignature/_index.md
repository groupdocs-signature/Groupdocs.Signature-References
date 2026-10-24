---
title: "DigitalSignature sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Sınıf, dijital imza özelliklerini içerir."
type: docs
url: /tr/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

Sınıf, dijital imza özelliklerini içerir.

DigitalSignature türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | Varsayılan parametrelerle bir dijital imza başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | Bilinen bir imza tanımlayıcısı ile bir dijital imza başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | Belirtilen X509 mağazasından ilk sertifikayı kullanarak bir DigitalSignature başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | Belirtilen X509 mağazası ve sertifika indeksi temelinde bir DigitalSignature başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | Belirtilen sertifika ile bir dijital imza başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | Barkod imza örneğini klonlar. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | Bu imzayı başka bir imza ile eşitlik açısından karşılaştırır. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | Dijital imza için hash kodunu döndürür. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Tüm sistem X509 sertifika mağazalarından dijital imzaları yükle. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Bir sertifika depolama alanından dijital imzaları yükle. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Bir sertifika depolama alanından dijital imzaları yükle. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Belirli bir konuma yerleştirilmiş dijital sertifika depolama alanından dijital imzaları yükle. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Belirli bir konuma yerleştirilmiş dijital sertifika depolama alanından dijital imzaları yükler. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Dijital imza ile ilişkili X509 sertifikası. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Sertifikanın özel mağaza adı. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Sertifikanın mağaza konumu. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Sertifikanın mağaza adı. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | İmzalama amacı yorumu. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Dijital imza geçerlidir ve belge değiştirilmemiştir. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Belgenin imzalandığı zaman. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Bir sertifikanın parmak izi. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | XAdES türü ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
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
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
