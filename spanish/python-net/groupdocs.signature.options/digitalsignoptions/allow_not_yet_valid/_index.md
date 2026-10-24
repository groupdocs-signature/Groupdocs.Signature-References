---
title: "allow_not_yet_valid propiedad"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado."
type: docs
url: /es/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

La bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado. El valor predeterminado es False; firmar con dicho certificado genera `GroupDocsSignatureException` y el documento no se firma.

Los validadores informan que una firma realizada antes de que el certificado sea válido no es válida. Ese certificado suele emitirse para una fecha posterior, o el reloj del ordenador está incorrecto. Cuando esta bandera es True, el documento se firma y se escribe una advertencia en el registrador configurado en [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

El certificado se compara con la hora actual en UTC. La bandera se aplica a los mismos certificados que [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), que controla los certificados cuyo período de validez ha finalizado.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Ver también
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
