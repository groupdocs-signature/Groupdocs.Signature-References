---
title: "ReturnContentType"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica el tipo de archivo del contenido de imagen devuelto de la firma Barcode cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa que se devolverá el contenido de imagen Barcode en su formato original. Este formato de imagen se especifica en Formatgroupdocs.signature.domain/barcodesignature/format. Los valores compatibles posibles son FileType.JPEG FileType.PNG FileType.BMP. Si el formato proporcionado no es compatible, entonces el contenido de imagen Barcode se devolverá en formato .png."
type: docs
weight: 50
url: /es/net/groupdocs.signature.options/barcodesearchoptions/returncontenttype/
---
## BarcodeSearchOptions.ReturnContentType property

Especifica el tipo de archivo del contenido de imagen devuelto de la firma Barcode cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa que se devolverá el contenido de imagen Barcode en su formato original. Este formato de imagen se especifica en [`Format`](../../../groupdocs.signature.domain/barcodesignature/format). Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, entonces el contenido de imagen Barcode se devolverá en formato .png.

```csharp
public FileType ReturnContentType { get; set; }
```

### Ver también

* class [FileType](../../../groupdocs.signature.domain/filetype)
* class [BarcodeSearchOptions](../../barcodesearchoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
