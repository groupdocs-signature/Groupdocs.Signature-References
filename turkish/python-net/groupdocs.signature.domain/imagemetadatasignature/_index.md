---
title: "ImageMetadataSignature sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bir görüntü meta verisi imzasını temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

Bir görüntü meta verisi imzasını temsil eder.

Resim belgeleri için meta veri imzaları, EXIF gibi resim meta veri standartlarına dayalı elektronik imzalardır. Her imza, (0‑65535) aralığında sayısal bir tanımlayıcı ile tanımlanır ve çeşitli tiplerde (metin, tarih/saat, tamsayı, kayan nokta) bir değer saklar.

ImageMetadataSignature türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | Belirtilen tanımlayıcı ve değerle bir Image Metadata Signature başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | Metadata Signature örneğini kopyalar. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | Verilen değerle bir ImageMetadataSignature örneğini klonlar. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | Belirtilen imza nesnesinin bu örnekle eşit olup olmadığını belirler. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | İmza için hash kodunu döndürür. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | Meta veri imza değerini bir boolean'a dönüştürür. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | Meta veri imza değerini bir `datetime.datetime`'a dönüştürür. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | Meta veri imza değerini bir `datetime`'a dönüştürür. |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Decimal'a dönüştürür. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | Meta veri imza değerini bir decimal'a dönüştürür. |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | Float'a dönüştürür. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | Metadata imza değerini float tipine dönüştürür. |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | Metadata imza değerini integer tipine dönüştürür. |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | Long'a dönüştürür. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | Float tipine dönüştürür. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | Metadata imza değerini float tipine dönüştürür. |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | Meta veri imza değerini bir string'e dönüştürür. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | Meta veri imza değerini belirtilen formatı kullanarak bir string'e dönüştürür. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | Belirtilen formatta bir dizeye dönüştürür. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (kalıtım alınan [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (kalıtım alınan [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | Standart Image Metadata imzasının açıklaması. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | Image Metadata imzasının tanımlayıcısı. Önceden tanımlı Id değerine sahip standart Signature içeren `GroupDocs.Signature.Domain.ImageMetadataSignatures` sınıfına bakın. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | Metadata değerinin boyutu. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | İmza oluşturma tarihi. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | İmza değer özelliklerini kodlamak ve çözmek için kullanılan [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) uygulaması. (kalıtım alınan [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bu imzanın belgeden silinip silinmediğini gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | İmzanın yüksekliği. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bu bileşenin bir imza (`True`) mı yoksa belge içeriği (`False`) mı olduğunu gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | İmzanın sol konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | İmzanın değiştirilme tarihi. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | Benzersiz meta veri adı. ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) üzerinden devralınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | İmzanın bulunduğu sayfa numarası. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | İmzanın benzersiz tanımlayıcısı, güncelleme veya silme işlemleriyle belgede imzayı değiştirmek için kullanılır. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | İmza türü. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | İmzanın üst konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | Meta veri değer türü. ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) üzerinden devralınmıştır) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | Meta veri nesnesi. ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) üzerinden devralınmıştır) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | İmzanın genişliği. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |

### Örnek

```python
from datetime import datetime

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
