---
title: ImageMetadataSignature
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Contiene propiedades de firma de metadatos de imagen.
type: docs
weight: 570
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
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Crea una firma de metadatos de imagen con ID y valor |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtener o establecer la fecha de creación de la firma. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtiene o establece la implementación de[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interfaz para codificar y decodificar propiedades de valor de firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtener el indicador que indica si esta firma se eliminó del documento. Esta propiedad se usa solo para registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Valor de solo lectura para obtener una descripción de la firma de metadatos de imagen estándar |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | El identificador de la firma de metadatos de imagen. VerImageMetadataSignatures clase que contiene Firma estándar con valor de Id predefinido. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenga o establezca un indicador para indicar si este componente es Firma o contenido de documento. Esta propiedad se usa con el método Actualizar para establecer el elemento como firma (verdadero) o elemento de documento (falso). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtener o establecer la fecha de modificación de la firma. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Especifica un nombre de metadatos único. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica en qué página se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador de firma único para modificar la firma en el documento sobre los métodos Actualizar o Eliminar. Esta propiedad se establecerá automáticamente después de que se llame al método Firmar o Buscar. Si esta propiedad se guardó antes, se puede establecer manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Valor de solo lectura para obtener el tamaño de los metadatos value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Especifica el tipo de valor de metadatos. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Especifica el objeto de metadatos. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Clonar instancia de firma de metadatos. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Instancia de firma de metadatos de imagen clonada con valor dado. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtener objeto del valor de la firma de metadatos sobre la deserialización. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtener objeto de texto de firma de metadatos sobre deserialización. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Anula el método GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Convierte a booleano. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Convierte a DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Convierte a DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Convierte a decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Convierte a decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Convierte a Doble. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Convierte a Doble. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Convierte a entero. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Convierte a largo. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Convierte a float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Convierte a float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Convierte a cadena con anular el método ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Convierte a cadena con formato especificado |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Convierte a cadena con formato especificado |

### Ver también

* class [MetadataSignature](../metadatasignature)
* espacio de nombres [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
