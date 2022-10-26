---
title: MetadataSignature
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Contiene propiedades de firma de metadatos.
type: docs
weight: 590
url: /es/net/groupdocs.signature.domain/metadatasignature/
---
## MetadataSignature class

Contiene propiedades de firma de metadatos.

```csharp
public abstract class MetadataSignature : BaseSignature
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtener o establecer la fecha de creación de la firma. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtiene o establece la implementación de[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interfaz para codificar y decodificar propiedades de valor de firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtener el indicador que indica si esta firma se eliminó del documento. Esta propiedad se usa solo para registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtenga o establezca un indicador para indicar si este componente es Firma o contenido de documento. Esta propiedad se usa con el método Actualizar para establecer el elemento como firma (verdadero) o elemento de documento (falso). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtener o establecer la fecha de modificación de la firma. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Especifica un nombre de metadatos único. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica en qué página se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador de firma único para modificar la firma en el documento sobre los métodos Actualizar o Eliminar. Esta propiedad se establecerá automáticamente después de que se llame al método Firmar o Buscar. Si esta propiedad se guardó antes, se puede establecer manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Especifica el objeto de metadatos. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone_1)() | Clonar instancia de firma de metadatos. |
| virtual [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone)(object) | Clonar instancia de firma de metadatos con valor dado. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata)() | Obtener objeto del valor de la firma de metadatos sobre la deserialización. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata_1)(IDataEncryption) | Obtener objeto de texto de firma de metadatos sobre deserialización. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Anula el método GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Convierte a booleano. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime)() | Convierte a DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime_1)(IFormatProvider) | Convierte a DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal)() | Convierte a decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal_1)(IFormatProvider) | Convierte a decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble)() | Convierte a Doble. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble_1)(IFormatProvider) | Convierte a Doble. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Convierte a entero. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle)() | Convierte a float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle_1)(IFormatProvider) | Convierte a float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring)() | Convierte a cadena con anular el método ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_1)(string) | Convierte a cadena con formato especificado |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_2)(string, IFormatProvider) | Convierte a cadena con formato especificado |

### Ver también

* class [BaseSignature](../basesignature)
* espacio de nombres [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
