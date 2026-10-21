---
title: "BarcodeSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas de código de barras."
type: docs
weight: 1440
url: /es/net/groupdocs.signature.options/barcodesearchoptions/
---
## BarcodeSearchOptions class

Representa opciones de búsqueda para firmas de código de barras.

```csharp
public class BarcodeSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarcodeSearchOptions](barcodesearchoptions#constructor)() | Inicializa una nueva instancia de la clase BarcodeSearchOptions con valores predeterminados. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_1)(BarcodeType) | Inicializa una nueva instancia de la clase BarcodeSearchOptions con el valor del tipo de codificación. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_2)(BarcodeType, string) | Inicializa una nueva instancia de la clase BarcodeSearchOptions con los valores de tipo de codificación y texto. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [EncodeType](../../groupdocs.signature.options/barcodesearchoptions/encodetype) { get; set; } | Especifica la propiedad Tipo de Codificación para buscar códigos de barras. Si este valor no está establecido, la búsqueda se procesa para todos los tipos de códigos de barras compatibles. |
| [MatchType](../../groupdocs.signature.options/barcodesearchoptions/matchtype) { get; set; } | Obtiene o establece la búsqueda de Tipo de Coincidencia de texto de código de barras. Se usa solo cuando la propiedad Text está establecida. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ReturnContent](../../groupdocs.signature.options/barcodesearchoptions/returncontent) { get; set; } | Obtiene o establece la bandera para capturar el contenido de imagen del código de barras de la firma en la página del documento. Si esta bandera se establece en true, el contenido de imagen de la firma de código de barras mantendrá los datos de imagen sin procesar en el formato requerido [`ReturnContentType`](./returncontenttype). Por defecto, esta opción está deshabilitada. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesearchoptions/returncontenttype) { get; set; } | Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa devolver el contenido de imagen del código de barras en su formato original. Este formato de imagen se especifica en [`Format`](../../groupdocs.signature.domain/barcodesignature/format). Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de imagen del código de barras en formato .png. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |
| [Text](../../groupdocs.signature.options/barcodesearchoptions/text) { get; set; } | Especifica el texto de la firma de código de barras si debe buscarse y coincidir. |

### Observaciones

**Learn more**

* Basic usage of search for Barcode electronic signature by GroupDocs.Signature: [How to eSearch Barcode signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures)
* Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
