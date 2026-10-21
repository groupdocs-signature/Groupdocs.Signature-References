---
title: "IDocumentInfo"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Define propiedades de descripción del documento."
type: docs
weight: 680
url: /es/net/groupdocs.signature.domain/idocumentinfo/
---
## IDocumentInfo interface

Define propiedades de descripción del documento.

```csharp
public interface IDocumentInfo
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [BarcodeSignatures](../../groupdocs.signature.domain/idocumentinfo/barcodesignatures) { get; } | Colección de firmas de código de barras del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [DigitalSignatures](../../groupdocs.signature.domain/idocumentinfo/digitalsignatures) { get; } | Colección de firmas digitales del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [Documents](../../groupdocs.signature.domain/idocumentinfo/documents) { get; } | Colección de todos los documentos existentes dentro de los archivos de archivo. Esta propiedad solo es compatible con tipos de documento de archivo. |
| [FileType](../../groupdocs.signature.domain/idocumentinfo/filetype) { get; set; } | Tipo de formato de archivo |
| [FormFields](../../groupdocs.signature.domain/idocumentinfo/formfields) { get; } | Colección de todos los campos de formulario compatibles existentes en el documento. Esta propiedad solo es compatible con tipos de documento PDF y de procesamiento de Word. |
| [FormFieldSignatures](../../groupdocs.signature.domain/idocumentinfo/formfieldsignatures) { get; } | Colección de firmas de campos de formulario del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [ImageSignatures](../../groupdocs.signature.domain/idocumentinfo/imagesignatures) { get; } | Colección de firmas de imagen del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [MaxPageHeight](../../groupdocs.signature.domain/idocumentinfo/maxpageheight) { get; set; } | Especifica la altura máxima de la página. |
| [MetadataSignatures](../../groupdocs.signature.domain/idocumentinfo/metadatasignatures) { get; } | Colección de firmas de metadatos del documento. |
| [PageCount](../../groupdocs.signature.domain/idocumentinfo/pagecount) { get; set; } | Recuento de páginas del documento. |
| [Pages](../../groupdocs.signature.domain/idocumentinfo/pages) { get; set; } | Colección de descripciones de páginas del documento. |
| [ProcessLogs](../../groupdocs.signature.domain/idocumentinfo/processlogs) { get; } | Colección de registros de procesos del historial del documento. |
| [QrCodeSignatures](../../groupdocs.signature.domain/idocumentinfo/qrcodesignatures) { get; } | Colección de firmas de código QR del documento añadidas o actualizadas mediante los métodos [`Signature`](../../groupdocs.signature/signature). |
| [Signatures](../../groupdocs.signature.domain/idocumentinfo/signatures) { get; } | Colección de firmas de todos los tipos de documento [`BaseSignature`](../basesignature). |
| [Size](../../groupdocs.signature.domain/idocumentinfo/size) { get; set; } | Tamaño del documento en bytes. |
| [TextSignatures](../../groupdocs.signature.domain/idocumentinfo/textsignatures) { get; } | Colección de firmas de texto de documento añadidas o actualizadas por los métodos [`Signature`](../../groupdocs.signature/signature). |
| [WidthForMaxHeight](../../groupdocs.signature.domain/idocumentinfo/widthformaxheight) { get; set; } | Especifica el ancho para la altura máxima de la página. |

### Ver también

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
