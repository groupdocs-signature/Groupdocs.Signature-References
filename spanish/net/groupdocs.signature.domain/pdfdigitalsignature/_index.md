---
title: "PdfDigitalSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Contiene propiedades de firma digital PDF."
type: docs
weight: 840
url: /es/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Contiene propiedades de firma digital PDF.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Inicialice la firma digital PDF sin certificado. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Cree una firma digital PDF con el certificado especificado. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Inicialice la firma digital PDF basada en el almacén X509 especificado. Se usará el primer certificado del almacén especificado. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Cree una firma digital PDF basada en el almacén X509 especificado y el índice del certificado. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtiene o establece el certificado X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Especifica el nombre de almacén personalizado del certificado. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Especifica la ubicación del almacén del certificado. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Especifica el nombre del almacén del certificado. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtiene o establece el comentario del propósito de la firma. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Información proporcionada por el firmante para permitir que el destinatario contacte al firmante y verifique la firma, p. ej., un número de teléfono. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtén o establece la fecha de creación de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtén la bandera que indica si esta firma fue eliminada del documento. Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtén o establece la bandera que indica si este componente es una Firma o contenido del documento. Esta propiedad se usa con el método Update para establecer el elemento como firma (true) o como elemento del documento (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Mantiene true si esta firma digital es válida y el documento no ha sido manipulado. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | El nombre de host de la CPU o la ubicación física de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtén o establece la fecha de modificación de la firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica la página en la que se encontró la firma. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | La razón de la firma, como (I agreeРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Forzar la visualización/ocultación de las propiedades de la firma. En caso de que ShowProperties sea true, el campo de firma tiene un formato de apariencia predefinido Firmado digitalmente por {[`ContactInfo`](./contactinfo)} Fecha: {Date} Razón: {[`Reason`](./reason)} Ubicación: {[`Location`](./location)} ShowProperties es true por defecto. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador único de la firma para modificar la firma en el documento mediante los métodos Update o Delete. Esta propiedad se establecerá automáticamente después de llamar a los métodos Sign o Search. Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtiene o establece la hora en que se firmó el documento. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtiene la huella digital de un certificado. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Marca de tiempo para la firma digital PDF. El valor predeterminado es null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Tipo de firma digital PDF. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Tipo XAdES [`XAdESType`](../digitalsignature/xadestype). El valor predeterminado es None (XAdES está desactivado). En este momento, el tipo de firma XAdES solo es compatible con documentos de hoja de cálculo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Clonar la instancia de firma de código de barras. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Sobrescribe el método GetHashCode |

### Ver también

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
