---
title: PresentationMetadataSignature
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Contiene propiedades de firma de metadatos de presentación.
type: docs
weight: 740
url: /es/net/groupdocs.signature.domain/presentationmetadatasignature/
---
## PresentationMetadataSignature class

Contiene propiedades de firma de metadatos de presentación.

```csharp
public sealed class PresentationMetadataSignature : MetadataSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor)(string) | Crea una firma de metadatos de presentación con un nombre predefinido y un valor vacío |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor_1)(string, object) | Crea una firma de metadatos de presentación con valores predefinidos |

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
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Especifica el tipo de valor de metadatos. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Especifica el objeto de metadatos. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone_1)() | Clonar instancia de firma de metadatos. |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone)(object) | Instancia de firma de metadatos de diapositivas de clonación con valor dado. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtener objeto del valor de la firma de metadatos sobre la deserialización. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtener objeto de texto de firma de metadatos sobre deserialización. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Anula el método GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Convierte a booleano. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Convierte a DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Convierte a DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Convierte a decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Convierte a decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Convierte a Doble. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Convierte a Doble. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Convierte a entero. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Convierte a float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Convierte a float. |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring)() | Convierte a cadena con anular el método ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Convierte a cadena con formato especificado |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Convierte a cadena con formato especificado |

### Ver también

* class [MetadataSignature](../metadatasignature)
* espacio de nombres [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
