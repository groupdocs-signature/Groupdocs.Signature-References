---
title: "ReturnContentType"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica el tipo de archivo del contenido de imagen devuelto de la firma QRCode cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa devolver el contenido de imagen QRCode en su formato original. Este formato de imagen se especifica en Formatgroupdocs.signature.domain/qrcodesignature/format. Los valores compatibles posibles son FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de imagen QRCode en .png original."
type: docs
weight: 60
url: /es/net/groupdocs.signature.options/qrcodesearchoptions/returncontenttype/
---
## QrCodeSearchOptions.ReturnContentType property

Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa devolver el contenido de imagen QR-Code en su formato original. Este formato de imagen se especifica en [`Format`](../../../groupdocs.signature.domain/qrcodesignature/format). Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de imagen QR-Code en .png original.

```csharp
public FileType ReturnContentType { get; set; }
```

### Ver también

* class [FileType](../../../groupdocs.signature.domain/filetype)
* class [QrCodeSearchOptions](../../qrcodesearchoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
