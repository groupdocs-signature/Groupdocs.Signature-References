---
title: "QrCodeSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Contiene propiedades de la firma QRcode."
type: docs
weight: 970
url: /es/net/groupdocs.signature.domain/qrcodesignature/
---
## QrCodeSignature class

Contiene propiedades de firma de código QR.

```csharp
public class QrCodeSignature : BaseSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QrCodeSignature](qrcodesignature)(string) | Inicialice el objeto QrCodeSignature con el identificador de firma que se obtuvo después del proceso de búsqueda. Este identificador único se utiliza para encontrar propiedades adicionales de esta firma en la capa de información de firmas del documento. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Content](../../groupdocs.signature.domain/qrcodesignature/content) { get; } | Especifica el contenido de la imagen de datos binarios del código QR del tipo [`Format`](./format). Por defecto, esta propiedad no se establecerá. Use la propiedad [`ReturnContent`](../../groupdocs.signature.options/qrcodesearchoptions/returncontent) para habilitar esta función. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtén o establece la fecha de creación de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtén la bandera que indica si esta firma fue eliminada del documento. Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas. |
| [EncodeType](../../groupdocs.signature.domain/qrcodesignature/encodetype) { get; } | Especifica el tipo de codificación del código QR. |
| [Format](../../groupdocs.signature.domain/qrcodesignature/format) { get; } | Especifica el formato de la imagen de la firma QR-code. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtén o establece la bandera que indica si este componente es una Firma o contenido del documento. Esta propiedad se usa con el método Update para establecer el elemento como firma (true) o como elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtén o establece la fecha de modificación de la firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica la página en la que se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador único de la firma para modificar la firma en el documento mediante los métodos Update o Delete. Esta propiedad se establecerá automáticamente después de llamar a los métodos Sign o Search. Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [Text](../../groupdocs.signature.domain/qrcodesignature/text) { get; } | Especifica el texto del código QR. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/qrcodesignature/clone)() | Clonar la instancia de QR-Code Signature. |
| override [Equals](../../groupdocs.signature.domain/qrcodesignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata)() | Obtener el objeto del Texto de la firma QR-Code tras la deserialización. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata_1)(IDataEncryption) | Obtener el objeto del Texto de la firma QR-Code tras la deserialización. |
| override [GetHashCode](../../groupdocs.signature.domain/qrcodesignature/gethashcode)() | Sobrescribe el método GetHashCode |

### Ver también

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
