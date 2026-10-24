---
title: "allow_not_yet_valid özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Henüz geçerlilik süresi başlamamış bir sertifikayla imzalama izin veren bayrak."
type: docs
url: /tr/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Henüz geçerlilik süresi başlamamış bir sertifika ile imzalamayı sağlayan bayrak. Varsayılan değer False'tur; bu tür bir sertifika ile imzalama `GroupDocsSignatureException` hatası oluşturur ve belge imzalanmaz.

Doğrulayıcılar, sertifikanın geçerli olmadan önce yapılmış bir imzayı geçersiz olarak rapor eder. Böyle bir sertifika genellikle daha sonraki bir tarih için düzenlenir veya bilgisayarın saati yanlıştır. Bu bayrak True olduğunda, belge imzalanır ve bir uyarı, [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) içinde ayarlanan günlüğe yazılır.

Sertifika, UTC'deki mevcut zamanla karşılaştırılır. Bu bayrak, geçerlilik süresi sona ermiş sertifikaları kontrol eden [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) ile aynı sertifikalar için geçerlidir.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Ayrıca Bakınız
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
