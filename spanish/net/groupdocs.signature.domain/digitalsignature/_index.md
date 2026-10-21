---
title: "DigitalSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Contiene propiedades de firma digital."
type: docs
weight: 150
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
| [DigitalSignature](digitalsignature#constructor)() | Inicializa la firma digital con parámetros predeterminados. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Inicializa la firma digital con SignatureId conocido. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Crea una firma digital con el certificado especificado. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Crea una firma digital basada en el almacén X509 especificado. Se usará el primer certificado del almacén especificado. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Crea una firma digital basada en el almacén X509 especificado y el índice del certificado. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Obtiene o establece el certificado X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Especifica el nombre de almacén personalizado del certificado. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Especifica la ubicación del almacén del certificado. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Especifica el nombre del almacén del certificado. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Obtiene o establece el comentario del propósito de la firma. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtén o establece la fecha de creación de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtén la bandera que indica si esta firma fue eliminada del documento. Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtén o establece la bandera que indica si este componente es una Firma o contenido del documento. Esta propiedad se usa con el método Update para establecer el elemento como firma (true) o como elemento del documento (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Mantiene true si esta firma digital es válida y el documento no ha sido manipulado. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtén o establece la fecha de modificación de la firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica la página en la que se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador único de la firma para modificar la firma en el documento mediante los métodos Update o Delete. Esta propiedad se establecerá automáticamente después de llamar a los métodos Sign o Search. Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Obtiene o establece la hora en que se firmó el documento. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Obtiene la huella digital de un certificado. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Tipo XAdES [`XAdESType`](./xadestype). El valor predeterminado es None (XAdES está desactivado). En este momento el tipo de firma XAdES solo es compatible con documentos de Spreadsheet. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Clonar la instancia de firma de código de barras. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Sobrescribe el método GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Cargar firmas digitales desde todos los almacenes de certificados X509 del sistema. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Cargar firmas digitales desde un almacenamiento de certificados. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Cargar firmas digitales desde un almacenamiento de certificados. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Cargar firmas digitales desde un almacenamiento de certificado digital ubicado en una ubicación específica. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Cargar firmas digitales desde un almacenamiento de certificado digital ubicado en una ubicación específica. |

### Ver también

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
