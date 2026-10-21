---
title: "DigitalVerifyOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Mantiene opciones para verificar la firma digital del documento."
type: docs
weight: 1570
url: /es/net/groupdocs.signature.options/digitalverifyoptions/
---
## DigitalVerifyOptions class

Mantiene opciones para verificar la firma digital del documento.

```csharp
public class DigitalVerifyOptions : VerifyOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DigitalVerifyOptions](digitalverifyoptions#constructor)() | Crea una opción de verificación digital con valores predeterminados. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_1)(Stream) | Crea una opción de verificación digital con el flujo de certificado proporcionado. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_2)(string) | Crea una opción de verificación digital con la ruta de archivo del certificado digital proporcionada. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Indicador para verificar cada página del documento. Por defecto el valor es true. |
| [Certificate](../../groupdocs.signature.options/digitalverifyoptions/certificate) { get; } | Obtiene el certificado X509Certificate2 a partir del FilePath del certificado o del Stream. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalverifyoptions/certificatefilepath) { get; set; } | Ruta del archivo del certificado digital. |
| [CertificateStream](../../groupdocs.signature.options/digitalverifyoptions/certificatestream) { get; set; } | Flujo del certificado digital. |
| [Comments](../../groupdocs.signature.options/digitalverifyoptions/comments) { get; set; } | Comentarios de la firma digital a validar. |
| [Contact](../../groupdocs.signature.options/digitalverifyoptions/contact) { get; set; } | Contacto de la firma a validar. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Extensiones adicionales para la verificación de opciones de firma alternativas. |
| [IssuerName](../../groupdocs.signature.options/digitalverifyoptions/issuername) { get; set; } | Nombre del emisor del certificado a validar. El valor distingue mayúsculas y minúsculas. Si esta propiedad está establecida, la verificación comprobará si el nombre del emisor de la firma contiene o es igual al valor proporcionado. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Indicador de propiedad válida. |
| [Location](../../groupdocs.signature.options/digitalverifyoptions/location) { get; set; } | Ubicación de la firma a validar. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Número de página del documento a verificar. Si la propiedad no está establecida, se verificarán todas las páginas del documento para la primera aparición. El valor mínimo es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opciones de página para especificar las páginas a verificar. |
| [Password](../../groupdocs.signature.options/digitalverifyoptions/password) { get; set; } | Contraseña del certificado digital si es requerida. |
| [Reason](../../groupdocs.signature.options/digitalverifyoptions/reason) { get; set; } | Motivo de la firma digital a validar. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Especifica la posición de la forma en el diseño del documento. Para verificar firmas en encabezados/pies de página. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalverifyoptions/signdatetimefrom) { get; set; } | Rango de fecha y hora de la firma digital a validar. El valor nulo será ignorado. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalverifyoptions/signdatetimeto) { get; set; } | Rango de fecha y hora de la firma digital a validar. El valor nulo será ignorado. |
| [SubjectName](../../groupdocs.signature.options/digitalverifyoptions/subjectname) { get; set; } | Nombre distinguido del sujeto del certificado a validar. El valor distingue mayúsculas y minúsculas. Si esta propiedad está establecida, la verificación comprobará si el nombre del sujeto de la firma contiene o es igual al valor proporcionado. |

### Observaciones

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings]()

### Ver también

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
