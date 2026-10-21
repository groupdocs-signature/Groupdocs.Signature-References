---
title: "MetadataSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas de Metadatos."
type: docs
weight: 1730
url: /es/net/groupdocs.signature.options/metadatasearchoptions/
---
## MetadataSearchOptions class

Representa opciones de búsqueda para firmas de Metadatos.

```csharp
public class MetadataSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MetadataSearchOptions](metadatasearchoptions)() | Inicializa una nueva instancia de la clase MetadataSearchOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [DataEncryption](../../groupdocs.signature.options/metadatasearchoptions/dataencryption) { get; set; } | Obtiene o establece la implementación de la interfaz [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) para descifrar todas las firmas de Metadatos dentro de esta colección de opciones. Si este valor está establecido, todas las firmas encontradas usarán este cifrado por defecto o su propio DataEncryption si se le asignó. |
| [IncludeBuiltinProperties](../../groupdocs.signature.options/metadatasearchoptions/includebuiltinproperties) { get; set; } | Indica si las propiedades de documento incorporadas, como estadísticas del documento, información, etc., deben incluirse en el resultado de búsqueda. Esta bandera tiene sentido para los tipos de archivo de documento de presentación, hoja de cálculo y procesamiento de texto. |
| [Name](../../groupdocs.signature.options/metadatasearchoptions/name) { get; set; } | Especifica el nombre de la firma de metadatos si debe buscarse y coincidir. |
| [NameMatchType](../../groupdocs.signature.options/metadatasearchoptions/namematchtype) { get; set; } | Obtiene o establece la búsqueda del tipo de coincidencia del nombre de metadatos. Se utiliza solo cuando la propiedad Name está establecida. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |

### Observaciones

**Learn more**

* Basic usage of search for Metadata electronic signature by GroupDocs.Signature: [How to eSearch Metadata signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures)
* Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Metadata signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
