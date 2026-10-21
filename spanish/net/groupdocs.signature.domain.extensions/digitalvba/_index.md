---
title: "DigitalVBA"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa la firma digital para proyectos VBA de Spreadsheets. Proporciona la capacidad de firmar el proyecto VBA en formatos específicos de documentos de Spreadsheets como Xlsm o Xltm. Si se añaden varias extensiones DigitalVBA a DigitalSignOptions.Extensions, solo la primera participa en la firma del documento."
type: docs
weight: 240
url: /es/net/groupdocs.signature.domain.extensions/digitalvba/
---
## DigitalVBA class

Representa la firma digital para proyectos VBA de Spreadsheets. Proporciona la capacidad de firmar el proyecto VBA en formatos específicos de documentos de Spreadsheets como Xlsm o Xltm. Si se añaden varias extensiones DigitalVBA a DigitalSignOptions.Extensions, solo la primera participa en la firma del documento.

```csharp
public class DigitalVBA : SignatureExtension
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DigitalVBA](digitalvba#constructor)(Stream, string) | Inicializa una nueva instancia de la clase DigitalVBA con flujo de certificado. |
| [DigitalVBA](digitalvba#constructor_1)(string, string) | Inicializa una nueva instancia de la clase DigitalVBA con archivo de certificado. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [CertificateFilePath](../../groupdocs.signature.domain.extensions/digitalvba/certificatefilepath) { get; } | Obtiene la ruta del archivo de certificado digital. Esta propiedad se usa solo si CertificateStream no está especificado. |
| [CertificateStream](../../groupdocs.signature.domain.extensions/digitalvba/certificatestream) { get; } | Obtiene el flujo de certificado digital. Si se especifica esta propiedad, siempre se usa en lugar de CertificateFilePath. |
| [Comments](../../groupdocs.signature.domain.extensions/digitalvba/comments) { get; set; } | Obtiene o establece los comentarios de la firma. |
| [Password](../../groupdocs.signature.domain.extensions/digitalvba/password) { get; set; } | Obtiene o establece la contraseña del certificado digital. |
| [SignOnlyVBAProject](../../groupdocs.signature.domain.extensions/digitalvba/signonlyvbaproject) { get; set; } | Obtiene o establece la configuración de firma solo del proyecto VBA. Si se establece en true, el documento SpreadSheet no se firmará, pero el proyecto VBA sí se firmará. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | Obtiene una copia de este objeto. |

### Ver también

* class [SignatureExtension](../signatureextension)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
