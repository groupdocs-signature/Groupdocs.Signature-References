---
title: MetadataSignOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Representa las opciones de firma de metadatos.
type: docs
weight: 1490
url: /es/net/groupdocs.signature.options/metadatasignoptions/
---
## MetadataSignOptions class

Representa las opciones de firma de metadatos.

```csharp
public class MetadataSignOptions : SignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MetadataSignOptions](metadatasignoptions#constructor)() | Inicializa una nueva instancia de la clase MetadataSignOptions con valores predeterminados. |
| [MetadataSignOptions](metadatasignoptions#constructor_1)(IEnumerable&lt;MetadataSignature&gt;) | Inicializa una nueva instancia de la clase MetadataSignOptions con Metadata. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Poner firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspecto de firma adicional. |
| [DataEncryption](../../groupdocs.signature.options/metadatasignoptions/dataencryption) { get; set; } | Obtiene o establece la implementación de[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)interfaz para cifrar todas las firmas de metadatos dentro de esta colección de opciones. Si se establece este valor, todas las firmas agregadas usarán este cifrado de forma predeterminada o su propio cifrado de datos si se asignó. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtener o establecer el tipo de documento de las opciones de firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para firmar. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar páginas a firmar. |
| [Signatures](../../groupdocs.signature.options/metadatasignoptions/signatures) { get; set; } | Obtiene o establece los Metadatos de la firma. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtener el tipo de firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición de orden Z de la firma de texto. Determina el orden de visualización de las firmas superpuestas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.signature.options/metadatasignoptions/add)(MetadataSignature) | Agregar instancia de MetadataSignature existente a la colección. |
| [AddImageSignature](../../groupdocs.signature.options/metadatasignoptions/addimagesignature)(ushort, object) | Crea una nueva ImageMetadataSignature con argumentos pasados y la agrega a la colección. |
| [AddPdfSignature](../../groupdocs.signature.options/metadatasignoptions/addpdfsignature)(string, object, string) | Crea un nuevo PdfMetadataSignature con argumentos pasados y lo agrega a la colección. |

### Observaciones

**Aprende más**

* Uso básico de creación de firma electrónica de metadatos por GroupDocs. Firma: [Cómo firmar un documento con la firma de metadatos](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature)
* Uso avanzado de configuración de firma electrónica de metadatos con GroupDocs.Firma: [Uso avanzado para firmar documentos electrónicos con firma de metadatos y configuraciones adicionales](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced)

### Ver también

* class [SignOptions](../signoptions)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
