---
title: "ImageDigitalSignOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones para incrustar la firma de esteganografía digital de Aspose.Imaging en imágenes raster."
type: docs
weight: 1630
url: /es/net/groupdocs.signature.options/imagedigitalsignoptions/
---
## ImageDigitalSignOptions class

Representa opciones para incrustar la firma digital (esteganografía) de Aspose.Imaging en imágenes rasterizadas.

```csharp
public class ImageDigitalSignOptions : SignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageDigitalSignOptions](imagedigitalsignoptions)() | Inicializa una nueva instancia de la clase ImageDigitalSignOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Coloca la firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apariencia adicional de la firma. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenga o establezca el Tipo de Documento de las Opciones de Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas. Compatible exclusivamente con firmas digitales en archivos PDF. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la firma. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar las páginas a firmar. |
| [Password](../../groupdocs.signature.options/imagedigitalsignoptions/password) { get; set; } | Contraseña utilizada para incrustar la firma digital. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenga el Tipo de Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición Z-order de la firma de texto. Determina el orden de visualización de firmas superpuestas. |

### Ver también

* class [SignOptions](../signoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
