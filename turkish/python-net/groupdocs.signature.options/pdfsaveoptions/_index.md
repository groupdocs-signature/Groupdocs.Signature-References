---
title: "PdfSaveOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "PDF belgeleri için kaydetme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

PDF belgeleri için kaydetme seçeneklerini temsil eder.

PdfSaveOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | PdfSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya biçimiyle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | PdfSaveOptions sınıfının yeni bir örneğini üzerine yazma bayrağıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya biçimi ve üzerine yazma bayrağıyla başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | İmzalı belgenin dosya formatı. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | Yazdırma, değiştirme ve veri çıkarma gibi PDF belge izinleri. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | İzin ayarlarını değiştirmek için gereken izin şifresi (birincil şifre). |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Çıktı dosya yolunda uzantı eksik olduğunda otomatik olarak eklenip eklenmeyeceğini belirleyen bayrak. Varsayılan değer False'tir. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Mevcut bir dosyanın yeni çıktı dosyasıyla üzerine yazılıp yazılmayacağını gösteren bayrak. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kaydedilen imzalı belgeyi korumak için kullanılan şifre. Görüntü belgeleri için desteklenmez. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | İmzalı belgeyi korumalı olarak kaydederken [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) içindeki şifrenin kullanılıp kullanılmayacağını gösteren bayrak. Varsayılan değer True'tir. Görüntü belgeleri için desteklenmez. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
