---
title: "MetadataSignOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de firma de Metadatos."
type: docs
weight: 1740
url: /es/net/groupdocs.signature.options/metadatasignoptions/
---
## MetadataSignOptions class

Representa opciones de firma de Metadatos.

```csharp
public class MetadataSignOptions : SignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MetadataSignOptions](metadatasignoptions#constructor)() | Inicializa una nueva instancia de la clase MetadataSignOptions con valores predeterminados. |
| [MetadataSignOptions](metadatasignoptions#constructor_1)(IEnumerable&lt;MetadataSignature&gt;) | Inicializa una nueva instancia de la clase MetadataSignOptions con Metadatos. |

## Properties

| Nombre | Descripción |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Coloca la firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apariencia adicional de la firma. |
| [DataEncryption](../../groupdocs.signature.options/metadatasignoptions/dataencryption) { get; set; } | Obtiene o establece la implementación de la interfaz [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) para encriptar todas las firmas de Metadatos dentro de esta colección de opciones. Si este valor se establece, todas las firmas añadidas usarán esta encriptación por defecto o su propia DataEncryption si se le asignó. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenga o establezca el Tipo de Documento de las Opciones de Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas. Compatible exclusivamente con firmas digitales en archivos PDF. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la firma. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar las páginas a firmar. |
| [Signatures](../../groupdocs.signature.options/metadatasignoptions/signatures) { get; set; } | Obtiene o establece los Metadatos de la firma. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenga el Tipo de Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición Z-order de la firma de texto. Determina el orden de visualización de firmas superpuestas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.signature.options/metadatasignoptions/add)(MetadataSignature) | Agrega una instancia existente de MetadataSignature a la colección. |
| [AddImageSignature](../../groupdocs.signature.options/metadatasignoptions/addimagesignature)(ushort, object) | Crea una nueva ImageMetadataSignature con los argumentos proporcionados y la agrega a la colección. |
| [AddPdfSignature](../../groupdocs.signature.options/metadatasignoptions/addpdfsignature)(string, object, string) | Crea una nueva PdfMetadataSignature con los argumentos proporcionados y la agrega a la colección. |

### Observaciones

**Learn more**

* Basic usage of creating Metadata electronic signature by GroupDocs.Signature: [How to eSign document with Metadata signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature)
* Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Metadata signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced)

### Ver también

* class [SignOptions](../signoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
