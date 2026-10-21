---
title: "CertificateVerifyOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Mantiene opciones para verificar documentos de certificado."
type: docs
weight: 1500
url: /es/net/groupdocs.signature.options/certificateverifyoptions/
---
## CertificateVerifyOptions class

Mantiene opciones para verificar documentos de certificado.

```csharp
public class CertificateVerifyOptions : VerifyOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CertificateVerifyOptions](certificateverifyoptions#constructor)() | Inicializa una nueva instancia de TextVerifyOptions con valores predeterminados. |
| [CertificateVerifyOptions](certificateverifyoptions#constructor_1)(string) | Inicializa una nueva instancia de CertificateVerifyOptions con el sujeto a verificar. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Indicador para verificar cada página del documento. Por defecto el valor es true. |
| [Expired](../../groupdocs.signature.options/certificateverifyoptions/expired) { get; } | Indica si el certificado está vencido según el resultado de la validación. La propiedad es de solo lectura. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Extensiones adicionales para la verificación de opciones de firma alternativas. |
| [Issuer](../../groupdocs.signature.options/certificateverifyoptions/issuer) { get; set; } | Especifique el emisor del certificado si debe verificarse. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Indicador de propiedad válida. |
| [MatchType](../../groupdocs.signature.options/certificateverifyoptions/matchtype) { get; set; } | Obtiene o establece la verificación del tipo de coincidencia de texto. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Número de página del documento a verificar. Si la propiedad no está establecida, se verificarán todas las páginas del documento para la primera aparición. El valor mínimo es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opciones de página para especificar las páginas a verificar. |
| [PerformChainValidation](../../groupdocs.signature.options/certificateverifyoptions/performchainvalidation) { get; set; } | Obtenga o establezca si el proceso de verificación debe proporcionar la validación de cadena X.509 usando la política de validación básica. Por defecto, este valor es true. |
| [SerialNumber](../../groupdocs.signature.options/certificateverifyoptions/serialnumber) { get; set; } | Especifique el número de serie del certificado si debe verificarse. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Especifica la posición de la forma en el diseño del documento. Para verificar firmas en encabezados/pies de página. |
| [Subject](../../groupdocs.signature.options/certificateverifyoptions/subject) { get; set; } | Especifique el sujeto del certificado si debe verificarse. |
| [Thumbprint](../../groupdocs.signature.options/certificateverifyoptions/thumbprint) { get; set; } | Especifique la huella digital del certificado si debe verificarse. |

### Observaciones

**Learn more**

* Basic usage of certificate documents by GroupDocs.Signature: [Preview Digital Certificates properties](https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

### Ver también

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
