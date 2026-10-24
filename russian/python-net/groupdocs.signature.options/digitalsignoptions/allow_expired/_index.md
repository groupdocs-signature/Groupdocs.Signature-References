---
title: "свойство allow_expired"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, позволяющий подписывать с сертификатом, срок действия которого истёк."
type: docs
url: /ru/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Флаг, позволяющий подписывать с сертификатом, срок действия которого истек. Значение по умолчанию — False; подпись с просроченным сертификатом вызывает `GroupDocsSignatureException`, и документ не подписывается.

Валидаторы считают подпись, сделанную с истёкшим сертификатом, недействительной. Устанавливайте это свойство в True только тогда, когда такая подпись всё равно необходима, например для тестирования со старым сертификатом. Затем документ подписывается, и в журнал, настроенный в [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/), записывается предупреждение.

Сертификат сравнивается с текущим временем в UTC, а не с [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). Флаг применяется к сертификату, указанному в [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) или [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), а при подписании электронных таблиц — к сертификату первого расширения [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/). Цифровые подписи изображений не используют сертификат и не проверяются. Сертификат, срок действия которого ещё не начался, контролируется параметром [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### См. также
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
