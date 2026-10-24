---
title: "allow_expired propiedad"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La bandera que permite firmar con un certificado cuyo período de validez ha terminado."
type: docs
url: /es/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

La bandera que permite firmar con un certificado cuyo período de validez ha finalizado. El valor predeterminado es False; firmar con un certificado expirado genera `GroupDocsSignatureException` y el documento no se firma.

Los validadores informan que una firma realizada con un certificado expirado no es válida. Establezca esta propiedad en True solo cuando necesite esa firma de todos modos, por ejemplo para probar con un certificado antiguo. Entonces el documento se firma y se escribe una advertencia en el registrador configurado en [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

El certificado se compara con la hora actual en UTC, no con [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). La bandera se aplica al certificado proporcionado por [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) o [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), y, cuando se firma una hoja de cálculo, al certificado de la primera extensión [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/). Las firmas digitales de imágenes no utilizan un certificado y no se verifican. Un certificado cuyo período de validez aún no ha comenzado está controlado por [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Ver también
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
