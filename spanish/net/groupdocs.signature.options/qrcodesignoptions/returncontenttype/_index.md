---
title: "ReturnContentType"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica el tipo de archivo del contenido de imagen devuelto de la firma QRCode cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa que se devuelve el contenido de la imagen QRCode en su formato original. Este formato de imagen se especifica en Formatgroupdocs.signature.domain/qrcodesignature/format. Los valores compatibles posibles son FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen QRCode en formato .png."
type: docs
weight: 110
url: /es/net/groupdocs.signature.options/qrcodesignoptions/returncontenttype/
---
## QrCodeSignOptions.ReturnContentType property

Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa que se devuelve el contenido de la imagen QR-Code en su formato original. Este formato de imagen se especifica en [`Format`](../../../groupdocs.signature.domain/qrcodesignature/format). Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen QR-Code en formato .png.

```csharp
public FileType ReturnContentType { get; set; }
```

### Ver también

* class [FileType](../../../groupdocs.signature.domain/filetype)
* class [QrCodeSignOptions](../../qrcodesignoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
