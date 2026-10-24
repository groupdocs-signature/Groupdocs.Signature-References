---
title: "DigitalVBA sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Elektronik tablolar VBA projeleri için dijital imzayı temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Elektronik tablolar VBA projeleri için dijital imzayı temsil eder.

`Xlsm` veya `Xltm` gibi elektronik tablo belge formatlarında bir VBA projesini imzalama yeteneği sağlar. Birden fazla [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) uzantısı [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/) öğesine eklenirse, imzalama sırasında yalnızca ilk olanı kullanılır.

DigitalVBA türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | DigitalVBA sınıfının yeni bir örneğini bir sertifika dosyasıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | DigitalVBA sınıfının yeni bir örneğini bir sertifika akışıyla başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Bu nesnenin bir kopyasını alır. ([`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/) üzerinden devralınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Dijital sertifika dosya yolu, yalnızca `CertificateStream` belirtilmemişse kullanılır. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Dijital sertifika akışı. Bu özellik belirtilirse her zaman CertificateFilePath yerine kullanılır. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | İmza yorumları. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Dijital sertifikanın parolası. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | Yalnızca VBA projesinin imzalanıp imzalanmayacağını belirleyen ayar. True olduğunda, elektronik tablo belgesi kendisi imzalanmaz; yalnızca VBA projesi imzalanır. |

### Örnek

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Elektronik tablo içindeki makroları imzala
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # VBA projesini dijital olarak imzalamak için uzantı ekle
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # VBA proje imza bölümünün eklendiğini doğrula
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Ayrıca Bakınız
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
