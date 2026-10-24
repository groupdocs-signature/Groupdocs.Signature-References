---
title: "allow_expired özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Geçerlilik süresi sona ermiş bir sertifikayla imzalama izin veren bayrak."
type: docs
url: /tr/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Süre sonu geçmiş bir sertifika ile imzalamayı sağlayan bayrak. Varsayılan değer False'tur; süresi dolmuş bir sertifika ile imzalama `GroupDocsSignatureException` hatası oluşturur ve belge imzalanmaz.

Doğrulayıcılar, süresi dolmuş bir sertifika ile yapılmış imzayı geçersiz olarak rapor eder. Bu özelliği yalnızca böyle bir imzaya yine de ihtiyacınız olduğunda, örneğin eski bir sertifika ile test yapmak için True olarak ayarlayın. Belge daha sonra imzalanır ve bir uyarı, [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) içinde ayarlanan günlüğe yazılır.

Sertifika, UTC'deki mevcut zamanla karşılaştırılır, [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) ile değil. Bu bayrak, [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) veya [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/) tarafından sağlanan sertifika için geçerlidir ve bir elektronik tablo imzalandığında, ilk [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) uzantısının sertifikasına da uygulanır. Görüntülerin dijital imzaları bir sertifika kullanmaz ve kontrol edilmez. Henüz geçerlilik süresi başlamamış bir sertifika, [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) tarafından kontrol edilir.

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Ayrıca Bakınız
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
