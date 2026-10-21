---
title: "FormFieldSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas de Formfield."
type: docs
weight: 1590
url: /es/net/groupdocs.signature.options/formfieldsearchoptions/
---
## FormFieldSearchOptions class

Representa opciones de búsqueda para firmas de campos de formulario.

```csharp
public class FormFieldSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FormFieldSearchOptions](formfieldsearchoptions)() | Inicializa una nueva instancia de la clase FormFieldSearchOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [Name](../../groupdocs.signature.options/formfieldsearchoptions/name) { get; set; } | Especifica el patrón de expresión regular del nombre de la firma de campo de formulario si debe buscarse. Puedes usarlo simplemente como "text" o una expresión regular como "abc\\d+". El valor predeterminado es una cadena vacía. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |
| [Type](../../groupdocs.signature.options/formfieldsearchoptions/type) { get; set; } | Especifica el tipo de firma de campo de formulario si debe buscarse. El valor predeterminado es null. |
| [Value](../../groupdocs.signature.options/formfieldsearchoptions/value) { get; set; } | Especifica el valor de la firma de campo de formulario si debe buscarse. El valor predeterminado es null. |

### Observaciones

**Learn more**

* Basic usage of search for FormField electronic signature by GroupDocs.Signature: [How to eSearch FormField signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures)
* Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: [Advanced usage of eSearch FormField signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
