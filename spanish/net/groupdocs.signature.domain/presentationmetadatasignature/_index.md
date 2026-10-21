---
title: "PresentationMetadataSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Contiene propiedades de firma de metadatos de presentación."
type: docs
weight: 920
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
| [PresentationMetadataSignature](presentationmetadatasignature#constructor)(string) | Crea Presentation Metadata Signature con nombre predefinido y valor vacío. |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor_1)(string, object) | Crea Presentation Metadata Signature con valores predefinidos. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtén o establece la fecha de creación de la firma. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Obtiene o establece la implementación de la interfaz [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) para codificar y decodificar las propiedades Value de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtén la bandera que indica si esta firma fue eliminada del documento. Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtén o establece la bandera que indica si este componente es una Firma o contenido del documento. Esta propiedad se usa con el método Update para establecer el elemento como firma (true) o como elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtén o establece la fecha de modificación de la firma. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Especifica un nombre de metadato único. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica la página en la que se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador único de la firma para modificar la firma en el documento mediante los métodos Update o Delete. Esta propiedad se establecerá automáticamente después de llamar a los métodos Sign o Search. Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Especifica el tipo de valor del metadato. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Especifica el objeto de metadato. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone_1)() | Clona la instancia de Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone)(object) | Clona la instancia de Slides Metadata Signature con el valor dado. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Obtiene el objeto del Valor de Metadata Signature durante la deserialización. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Obtiene el objeto del Texto de Metadata Signature durante la deserialización. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Sobrescribe el método GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Convierte a booleano. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Convierte a DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Convierte a DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Convierte a Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Convierte a Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Convierte a Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Convierte a Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Convierte a entero. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Convierte a float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Convierte a float. |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring)() | Convierte a String con el método sobrescrito ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Convierte a String con formato especificado |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Convierte a String con formato especificado |

### Ver también

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
