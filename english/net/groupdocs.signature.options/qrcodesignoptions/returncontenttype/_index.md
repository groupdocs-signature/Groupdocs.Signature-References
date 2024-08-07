---
title: ReturnContentType
second_title: GroupDocs.Signature for .NET API Reference
description: Specifies file type of returned image content of the QRCode signature when ReturnContent property is enabled. By default it set to Null. That means to return QRCode image content in original format. This image format is specified at Formatgroupdocs.signature.domain/qrcodesignature/format Possible supported values are FileType.JPEG FileType.PNG FileType.BMP. If provided format is not supported than QRCode image content in .png format will be returned.
type: docs
weight: 110
url: /net/groupdocs.signature.options/qrcodesignoptions/returncontenttype/
---
## QrCodeSignOptions.ReturnContentType property

Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. By default it set to Null. That means to return QR-Code image content in original format. This image format is specified at [`Format`](../../../groupdocs.signature.domain/qrcodesignature/format) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than QR-Code image content in .png format will be returned.

```csharp
public FileType ReturnContentType { get; set; }
```

### See Also

* class [FileType](../../../groupdocs.signature.domain/filetype)
* class [QrCodeSignOptions](../../qrcodesignoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
