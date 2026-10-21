---
title: "DocumentInfo"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Define propiedades de descripción del documento."
type: docs
weight: 160
url: /es/net/groupdocs.signature.domain/documentinfo/
---
## DocumentInfo class

Define propiedades de descripción del documento.

```csharp
public class DocumentInfo : IDocumentInfo
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocumentInfo](documentinfo)() | Inicializa una nueva instancia de la clase [`DocumentInfo`](../documentinfo). |

## Properties

| Nombre | Descripción |
| --- | --- |
| [BarcodeSignatures](../../groupdocs.signature.domain/documentinfo/barcodesignatures) { get; } | Colección de firmas de código de barras del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [DigitalSignatures](../../groupdocs.signature.domain/documentinfo/digitalsignatures) { get; } | Colección de firmas digitales del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [Documents](../../groupdocs.signature.domain/documentinfo/documents) { get; } | Colección de todos los documentos existentes dentro de los archivos de archivo. Esta propiedad solo es compatible con tipos de documento de archivo. |
| [FileType](../../groupdocs.signature.domain/documentinfo/filetype) { get; set; } | Tipo de formato de archivo. |
| [FormFields](../../groupdocs.signature.domain/documentinfo/formfields) { get; } | Colección de todos los campos de formulario compatibles existentes en el documento. Esta propiedad solo es compatible con tipos de documento PDF y de procesamiento de Word. |
| [FormFieldSignatures](../../groupdocs.signature.domain/documentinfo/formfieldsignatures) { get; } | Colección de firmas de campos de formulario del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [ImageSignatures](../../groupdocs.signature.domain/documentinfo/imagesignatures) { get; } | Colección de firmas de imagen del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [MaxPageHeight](../../groupdocs.signature.domain/documentinfo/maxpageheight) { get; set; } | Especifica la altura máxima de la página. |
| [MetadataSignatures](../../groupdocs.signature.domain/documentinfo/metadatasignatures) { get; } | Colección de firmas de metadatos del documento. |
| [PageCount](../../groupdocs.signature.domain/documentinfo/pagecount) { get; set; } | Recuento de páginas del documento. |
| [Pages](../../groupdocs.signature.domain/documentinfo/pages) { get; set; } | Colección de descripciones de páginas del documento. |
| [ProcessLogs](../../groupdocs.signature.domain/documentinfo/processlogs) { get; } | Colección de procesos de historial de documentos como Sign, Update, Delete. |
| [QrCodeSignatures](../../groupdocs.signature.domain/documentinfo/qrcodesignatures) { get; } | Colección de firmas de código QR del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [Signatures](../../groupdocs.signature.domain/documentinfo/signatures) { get; } | Colección de firmas de todos los tipos de documento [`BaseSignature`](../basesignature). |
| [Size](../../groupdocs.signature.domain/documentinfo/size) { get; set; } | Tamaño del documento en bytes. |
| [TextSignatures](../../groupdocs.signature.domain/documentinfo/textsignatures) { get; } | Colección de firmas de texto de documentos. |
| [WidthForMaxHeight](../../groupdocs.signature.domain/documentinfo/widthformaxheight) { get; set; } | Especifica el ancho para la altura máxima de la página. |

### Ver también

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
