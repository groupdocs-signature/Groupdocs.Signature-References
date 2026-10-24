---
title: "свойство allow_not_yet_valid"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, позволяющий подписывать с сертификатом, срок действия которого ещё не начался."
type: docs
url: /ru/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Флаг, позволяющий подписывать с сертификатом, срок действия которого еще не начался. Значение по умолчанию — False; подпись с таким сертификатом вызывает `GroupDocsSignatureException`, и документ не подписывается.

Валидаторы считают подпись, сделанную до того, как сертификат стал действительным, недействительной. Такой сертификат обычно выдан на более позднюю дату, либо часы компьютера неверны. Когда этот флаг установлен в True, документ подписывается, и в журнал, настроенный в [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/), записывается предупреждение.

Сертификат сравнивается с текущим временем в UTC. Флаг применяется к тем же сертификатам, что и [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), который контролирует сертификаты, срок действия которых истёк.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### См. также
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
