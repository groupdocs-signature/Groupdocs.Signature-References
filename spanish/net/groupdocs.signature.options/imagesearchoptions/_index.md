---
title: "ImageSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas de imagen."
type: docs
weight: 1660
url: /es/net/groupdocs.signature.options/imagesearchoptions/
---
## ImageSearchOptions class

Representa opciones de búsqueda para firmas de imagen.

```csharp
public class ImageSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageSearchOptions](imagesearchoptions)() | Inicializa una nueva instancia de la clase ImageSearchOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [MaxContentSize](../../groupdocs.signature.options/imagesearchoptions/maxcontentsize) { get; set; } | Para un valor distinto de cero, este indicador especifica el tamaño máximo de las imágenes para el criterio de búsqueda. Por defecto, este indicador está establecido en cero y no afecta el resultado de la búsqueda. |
| [MinContentSize](../../groupdocs.signature.options/imagesearchoptions/mincontentsize) { get; set; } | Para un valor distinto de cero, este indicador especifica el tamaño mínimo de las imágenes para el criterio de búsqueda. Por defecto, este indicador está establecido en cero y no afecta el resultado de la búsqueda. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ReturnContent](../../groupdocs.signature.options/imagesearchoptions/returncontent) { get; set; } | Obtiene o establece el indicador para capturar el contenido de imagen de la firma en la página del documento. Si este indicador se establece en true, el contenido de la firma de imagen mantendrá los datos de imagen sin procesar en el formato requerido [`ReturnContentType`](./returncontenttype). Por defecto, esta opción está deshabilitada. |
| [ReturnContentType](../../groupdocs.signature.options/imagesearchoptions/returncontenttype) { get; set; } | Especifica el tipo de archivo del contenido devuelto de la firma de imagen cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa que se devolverá el contenido de la imagen en su formato original. Este formato de imagen se especifica en [`Format`](../../groupdocs.signature.domain/imagesignature/format). Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen en su formato original. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |

### Observaciones

**Learn more**

* Basic usage of search for Image electronic signature by GroupDocs.Signature: [How to eSearch Image signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures)
* Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Image signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
