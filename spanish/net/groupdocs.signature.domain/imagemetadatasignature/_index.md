---
title: "ImageMetadataSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Contiene propiedades de firma de metadatos de imagen."
type: docs
weight: 740
url: /es/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Contiene propiedades de firma de metadatos de imagen.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Crea Image Metadata Signature con Id y valor. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtén o establece la fecha de creación de la firma. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtiene o establece la implementación de la interfaz [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) para codificar y decodificar las propiedades Value de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtén la bandera que indica si esta firma fue eliminada del documento. Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Valor de solo lectura para obtener la descripción de la firma estándar Image Metadata signature. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | El identificador de la firma Image Metadata. Vea la clase ImageMetadataSignatures que contiene la firma estándar con un valor Id predefinido. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtén o establece la bandera que indica si este componente es una Firma o contenido del documento. Esta propiedad se usa con el método Update para establecer el elemento como firma (true) o como elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtén o establece la fecha de modificación de la firma. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Especifica un nombre de metadato único. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica la página en la que se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador único de la firma para modificar la firma en el documento mediante los métodos Update o Delete. Esta propiedad se establecerá automáticamente después de llamar a los métodos Sign o Search. Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Valor de solo lectura para obtener el tamaño del valor de Metadatos. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Especifica el tipo de valor del metadato. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Especifica el objeto de metadato. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Clona la instancia de Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Clonar la instancia Image Metadata Signature con el valor proporcionado. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtiene el objeto del Valor de Metadata Signature durante la deserialización. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtiene el objeto del Texto de Metadata Signature durante la deserialización. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Sobrescribe el método GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Convierte a booleano. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Convierte a DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Convierte a DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Convierte a Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Convierte a Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Convierte a Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Convierte a Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Convierte a entero. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Convierte a long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Convierte a float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Convierte a float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Convierte a String con el método sobrescrito ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Convierte a String con formato especificado |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Convierte a String con formato especificado |

### Ver también

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
