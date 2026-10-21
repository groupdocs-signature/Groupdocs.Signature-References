---
title: "TextSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Contiene propiedades de firma de texto."
type: docs
weight: 1190
url: /es/net/groupdocs.signature.domain/textsignature/
---
## TextSignature class

Contiene propiedades de firma de texto.

```csharp
public class TextSignature : BaseSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextSignature](textsignature)(string) | Inicializa el objeto TextSignature con el identificador de firma que se obtuvo después del proceso de búsqueda. Este identificador único se usa para encontrar propiedades adicionales de esta firma en la capa de información de firmas del documento. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtén o establece la fecha de creación de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtén la bandera que indica si esta firma fue eliminada del documento. Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtén o establece la bandera que indica si este componente es una Firma o contenido del documento. Esta propiedad se usa con el método Update para establecer el elemento como firma (true) o como elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtén o establece la fecha de modificación de la firma. |
| [Native](../../groupdocs.signature.domain/textsignature/native) { get; set; } | Especifica el atributo nativo. Es verdadero si la firma es específica del documento. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica la página en la que se encontró la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador único de la firma para modificar la firma en el documento mediante los métodos Update o Delete. Esta propiedad se establecerá automáticamente después de llamar a los métodos Sign o Search. Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma. |
| [SignatureImplementation](../../groupdocs.signature.domain/textsignature/signatureimplementation) { get; } | Especifica la implementación de la firma de texto. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [Text](../../groupdocs.signature.domain/textsignature/text) { get; set; } | Especifica el texto en la firma. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/textsignature/clone)() | Clonar la instancia de Text Signature. |
| override [Equals](../../groupdocs.signature.domain/textsignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| override [GetHashCode](../../groupdocs.signature.domain/textsignature/gethashcode)() | Sobrescribe el método GetHashCode |

### Ver también

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
