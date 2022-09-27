---
title: ReturnContentType
second_title: GroupDocs.Signature for .NET API Reference
description: Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. By default it set to Null. That means to return Barcode image content in original format. This image format is specified at Formatgroupdocs.signature.domain/barcodesignature/format Possible supported values are FileType.JPEG FileType.PNG FileType.BMP. If provided format is not supported than Barcode image content in .png format will be returned.
type: docs
weight: 70
url: /net/groupdocs.signature.options/barcodesignoptions/returncontenttype/
---
## BarcodeSignOptions.ReturnContentType property

Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. By default it set to Null. That means to return Barcode image content in original format. This image format is specified at [`Format`](../../../groupdocs.signature.domain/barcodesignature/format) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than Barcode image content in .png format will be returned.

```csharp
public FileType ReturnContentType { get; set; }
```

### See Also

* class [FileType](../../../groupdocs.signature.domain/filetype)
* class [BarcodeSignOptions](../../barcodesignoptions)
* namespace [GroupDocs.Signature.Options](../../barcodesignoptions)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->