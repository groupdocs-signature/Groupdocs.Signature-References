---
title: "AllowNotYetValid"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado. El valor predeterminado es false; firmar con dicho certificado lanza GroupDocsSignatureExceptiongroupdocs.signature/groupdocssignatureexception y el documento no se firma."
type: docs
weight: 30
url: /es/net/groupdocs.signature.options/digitalsignoptions/allownotyetvalid/
---
## DigitalSignOptions.AllowNotYetValid property

Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado. El valor predeterminado es false: firmar con dicho certificado lanza [`GroupDocsSignatureException`](../../../groupdocs.signature/groupdocssignatureexception), y el documento no se firma.

```csharp
public bool AllowNotYetValid { get; set; }
```

### Observaciones

Los validadores informan que una firma realizada antes de que el certificado sea válido no es válida. Normalmente ese certificado se emitió para una fecha posterior, o el reloj del equipo está incorrecto. Cuando esta propiedad es true, el documento se firma y se escribe una advertencia en el registrador configurado en [`SignatureSettings`](../../../groupdocs.signature/signaturesettings).

El certificado se compara con la hora actual en UTC. La bandera se aplica a los mismos certificados que [`AllowExpired`](../allowexpired), que controla los certificados cuyo período de validez ha finalizado.

### Ver también

* class [DigitalSignOptions](../../digitalsignoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
