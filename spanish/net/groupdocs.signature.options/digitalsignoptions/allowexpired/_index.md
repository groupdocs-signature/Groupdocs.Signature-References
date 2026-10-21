---
title: "AllowExpired"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez ha finalizado. El valor predeterminado es false; firmar con un certificado expirado lanza GroupDocsSignatureExceptiongroupdocs.signature/groupdocssignatureexception y el documento no se firma."
type: docs
weight: 20
url: /es/net/groupdocs.signature.options/digitalsignoptions/allowexpired/
---
## DigitalSignOptions.AllowExpired property

Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez ha finalizado. El valor predeterminado es false: firmar con un certificado expirado lanza [`GroupDocsSignatureException`](../../../groupdocs.signature/groupdocssignatureexception), y el documento no se firma.

```csharp
public bool AllowExpired { get; set; }
```

### Observaciones

Los validadores informan que una firma realizada con un certificado expirado no es válida. Establezca esta propiedad a true solo cuando necesite esa firma de todos modos, por ejemplo para probar con un certificado antiguo. Entonces el documento se firma y se escribe una advertencia en el registrador configurado en [`SignatureSettings`](../../../groupdocs.signature/signaturesettings).

El certificado se compara con la hora actual en UTC, no con [`SignTime`](../../../groupdocs.signature.domain/digitalsignature/signtime). La bandera se aplica al certificado proporcionado por [`CertificateFilePath`](../certificatefilepath), [`CertificateStream`](../certificatestream) o [`Signature`](../signature), y, cuando se firma una hoja de cálculo, al certificado de la primera extensión [`DigitalVBA`](../../../groupdocs.signature.domain.extensions/digitalvba). Las firmas digitales de imágenes no utilizan un certificado y no se verifican. Un certificado cuyo período de validez aún no ha comenzado está controlado por [`AllowNotYetValid`](../allownotyetvalid).

### Ver también

* class [DigitalSignOptions](../../digitalsignoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
