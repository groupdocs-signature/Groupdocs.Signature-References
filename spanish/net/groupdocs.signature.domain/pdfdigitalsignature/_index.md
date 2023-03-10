---
title: PdfDigitalSignature
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Contiene propiedades de firma digital en PDF.
type: docs
weight: 660
url: /es/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Contiene propiedades de firma digital en PDF.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Inicializar firma digital en PDF sin certificado. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Crear firma digital en PDF con el certificado especificado. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Inicialice la firma digital de PDF según el almacén X509 especificado. Se utilizará el primer certificado de la tienda especificada. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Crear firma digital en PDF basada en el almacén X509 especificado y el índice del certificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtiene o establece el certificado X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Especifica la ubicación de almacenamiento del certificado |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Especifica el nombre de almacenamiento del certificado. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtiene o establece el comentario de propósito de firma. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Información proporcionada por el firmante para permitir que un destinatario se comunique con el firmante para verificar la firma, por ejemplo, un número de teléfono. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtener o establecer la fecha de creación de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtener el indicador que indica si esta firma se eliminó del documento. Esta propiedad se usa solo para registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenga o establezca un indicador para indicar si este componente es Firma o contenido de documento. Esta propiedad se usa con el método Actualizar para establecer el elemento como firma (verdadero) o elemento de documento (falso). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Se mantiene verdadero si esta firma digital es válida y el documento no ha sido manipulado. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | El nombre de host de la CPU o la ubicación física de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtener o establecer la fecha de modificación de la firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica en qué página se encontró la firma. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | El motivo de la firma, como (Estoy de acuerdoРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Fuerza para mostrar/ocultar las propiedades de la firma. En caso de que ShowProperties sea verdadero, el campo signature tiene un formato de apariencia predefinido Firmado digitalmente por {[`ContactInfo`](./contactinfo)} Fecha: {Fecha} Motivo: {[`Reason`](./reason)} Ubicación: {[`Location`](./location) } ShowProperties es verdadero por defecto. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador de firma único para modificar la firma en el documento sobre los métodos Actualizar o Eliminar. Esta propiedad se establecerá automáticamente después de que se llame al método Firmar o Buscar. Si esta propiedad se guardó antes, se puede establecer manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtiene o establece la hora a la que se firmó el documento. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtiene la huella digital de un certificado. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Marca de tiempo para firma digital en PDF. El valor predeterminado es nulo. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Tipo de firma digital Pdf. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | tipo XAdES[`XAdESType`](../digitalsignature/xadestype) . El valor predeterminado es Ninguno (XAdES está desactivado). En este momento, el tipo de firma XAdES solo se admite para documentos de hoja de cálculo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Clonar instancia de firma de código de barras. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Anula el método GetHashCode |

### Ver también

* class [DigitalSignature](../digitalsignature)
* espacio de nombres [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
