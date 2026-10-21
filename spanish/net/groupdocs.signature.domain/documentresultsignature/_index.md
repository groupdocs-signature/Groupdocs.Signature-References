---
title: "DocumentResultSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Resultado del proceso de firma de documento de archivo para documento con firmas recién creadas."
type: docs
weight: 170
url: /es/net/groupdocs.signature.domain/documentresultsignature/
---
## DocumentResultSignature class

Resultado del proceso de firma de documento de archivo para documento con firmas recién creadas.

```csharp
public class DocumentResultSignature : BaseSignature, IResult
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Obtén o establece la fecha de creación de la firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Obtén la bandera que indica si esta firma fue eliminada del documento. Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas. |
| [DestinDocumentSize](../../groupdocs.signature.domain/documentresultsignature/destindocumentsize) { get; } | Devuelve el tamaño del documento de destino |
| [ErrorMessage](../../groupdocs.signature.domain/documentresultsignature/errormessage) { get; } | si el documento se procesó con error, esta propiedad contendrá el mensaje de error |
| [Failed](../../groupdocs.signature.domain/documentresultsignature/failed) { get; } | Lista de las firmas que fallaron durante el proceso [`BaseSignature`](../basesignature). |
| [FileName](../../groupdocs.signature.domain/documentresultsignature/filename) { get; } | Nombre de archivo del documento |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Especifica la altura de la firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Obtén o establece la bandera que indica si este componente es una Firma o contenido del documento. Esta propiedad se usa con el método Update para establecer el elemento como firma (true) o como elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Especifica la posición izquierda de la firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Obtén o establece la fecha de modificación de la firma. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Especifica la página en la que se encontró la firma. |
| [ProcessingTime](../../groupdocs.signature.domain/documentresultsignature/processingtime) { get; } | Devuelve el tiempo de ejecución del proceso en milisegundos |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificador único de la firma para modificar la firma en el documento mediante los métodos Update o Delete. Esta propiedad se establecerá automáticamente después de llamar a los métodos Sign o Search. Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Especifica el tipo de firma. |
| [SourceDocumentSize](../../groupdocs.signature.domain/documentresultsignature/sourcedocumentsize) { get; } | Devuelve el tamaño del documento de origen |
| [Succeeded](../../groupdocs.signature.domain/documentresultsignature/succeeded) { get; } | Lista de firmas procesadas exitosamente [`BaseSignature`](../basesignature). |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Especifica la posición superior de la firma. |
| [TotalSignatures](../../groupdocs.signature.domain/documentresultsignature/totalsignatures) { get; } | Devuelve el total de firmas procesadas |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Especifica el ancho de la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain/basesignature/clone)() | Clonar instancia de firma. |
| override [Equals](../../groupdocs.signature.domain/basesignature/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de la firma |
| override [GetHashCode](../../groupdocs.signature.domain/basesignature/gethashcode)() | Sobrescribe el método GetHashCode |

### Observaciones

**Learn more**

* More about signing documents withing archives using GroupDocs.Signature: [How to sign documents withing archives using C#](https://docs.groupdocs.com/signature/net/signing-archive-documents/)

### Ver también

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
