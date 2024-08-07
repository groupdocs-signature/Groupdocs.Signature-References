---
title: DoPaletteCorrection
second_title: GroupDocs.Signature for .NET API Reference
description: Gets or sets a value indicating whether palette correction is applied.
type: docs
weight: 40
url: /net/groupdocs.signature.options/gifsaveoptions/dopalettecorrection/
---
## GifSaveOptions.DoPaletteCorrection property

Gets or sets a value indicating whether palette correction is applied.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Remarks

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better.

### See Also

* class [GifSaveOptions](../../gifsaveoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
