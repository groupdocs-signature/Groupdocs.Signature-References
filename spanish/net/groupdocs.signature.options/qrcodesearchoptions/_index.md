---
title: "QrCodeSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas QRCode."
type: docs
weight: 1910
url: /es/net/groupdocs.signature.options/qrcodesearchoptions/
---
## QrCodeSearchOptions class

Representa opciones de búsqueda para firmas de código QR.

```csharp
public class QrCodeSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor)() | Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores predeterminados. |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor_1)(QrCodeType) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con el valor del tipo de codificación. |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor_2)(QrCodeType, string) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con los valores del tipo de codificación y del texto. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesearchoptions/dataencryption) { get; set; } | Obtiene o establece la implementación de la interfaz [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
| [EncodeType](../../groupdocs.signature.options/qrcodesearchoptions/encodetype) { get; set; } | Especifica la propiedad Tipo de Codificación para buscar QR-Codes. Si este valor no se establece, la búsqueda se procesa para todos los tipos de QR-Code compatibles. |
| [MatchType](../../groupdocs.signature.options/qrcodesearchoptions/matchtype) { get; set; } | Obtiene o establece la búsqueda del Tipo de Coincidencia de Texto QR-Code. Se utiliza solo cuando la propiedad Texto está establecida. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesearchoptions/returncontent) { get; set; } | Obtiene o establece la bandera para capturar el contenido de imagen QR-Code de la firma en la página del documento. Si esta bandera se establece en true, el contenido de imagen de la firma QR-Code mantendrá los datos de imagen sin procesar según el formato requerido [`ReturnContentType`](./returncontenttype). Por defecto, esta opción está deshabilitada. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesearchoptions/returncontenttype) { get; set; } | Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa devolver el contenido de imagen QR-Code en su formato original. Este formato de imagen se especifica en [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de imagen QR-Code en .png original. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |
| [Text](../../groupdocs.signature.options/qrcodesearchoptions/text) { get; set; } | Especifica el Texto de la Firma QR-Code si debe ser buscado y coincidir. |

### Observaciones

**Learn more**

* Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: [How to eSearch QR-Code signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
* Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: [Advanced usage of eSearch QR-Code signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
