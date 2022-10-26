---
title: DigitalSignature
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Contiene propiedades de firma digital.
type: docs
weight: 140
url: /es/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Contiene propiedades de firma digital.

```csharp
public class DigitalSignature : BaseSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Inicializar Firma digital con parámetros por defecto. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Inicializar firma digital con SignatureId conocido. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Crear firma digital con certificado especificado. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Crear firma digital basada en el almacén X509 especificado. Se utilizará el primer certificado de la tienda especificada. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Crear firma digital basada en el almacén X509 especificado y el índice del certificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtiene o establece el certificado X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Especifica la ubicación de almacenamiento del certificado |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Especifica el nombre de almacenamiento del certificado. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtiene o establece el comentario de propósito de firma. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtener o establecer la fecha de creación de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtener el indicador que indica si esta firma se eliminó del documento. Esta propiedad se usa solo para registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenga o establezca un indicador para indicar si este componente es Firma o contenido de documento. Esta propiedad se usa con el método Actualizar para establecer el elemento como firma (verdadero) o elemento de documento (falso). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Se mantiene verdadero si esta firma digital es válida y el documento no ha sido manipulado. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtener o establecer la fecha de modificación de la firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica en qué página se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador de firma único para modificar la firma en el documento sobre los métodos Actualizar o Eliminar. Esta propiedad se establecerá automáticamente después de que se llame al método Firmar o Buscar. Si esta propiedad se guardó antes, se puede establecer manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtiene o establece la hora a la que se firmó el documento. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtiene la huella digital de un certificado. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | tipo XAdES[`XAdESType`](./xadestype) . El valor predeterminado es Ninguno (XAdES está desactivado). En este momento, el tipo de firma XAdES solo se admite para documentos de hoja de cálculo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Clonar instancia de firma de código de barras. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Anula el método GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Cargar firma digital de todos los almacenes de certificados X509 del sistema. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Cargar firma digital del almacén de certificados X509 aprobado. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Cargar firma digital del almacén de certificados X509 aprobado. |

### Ver también

* class [BaseSignature](../basesignature)
* espacio de nombres [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
