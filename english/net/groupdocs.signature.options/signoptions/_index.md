---
title: SignOptions
second_title: GroupDocs.Signature for .NET API Reference
description: Represents the signature options.
type: docs
weight: 1600
url: /net/groupdocs.signature.options/signoptions/
---
## SignOptions class

Represents the signature options.

```csharp
public abstract class SignOptions
```

## Properties

| Name | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Put signature on all document pages. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Additional signature appearance. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Get or set the Document Type of the Signature Options [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signature Extensions. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Gets or sets document page number for signing. Minimal and default value is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options to specify pages to be signed. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Get the Signature Type [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Gets or sets the Z-order position of text signature. Determines the display order of overlapping signatures. |

### Remarks

**Learn more**

* See more simple examples on creating various electronic signatures with GroupDocs.Signature: [Electronic signature types](https://docs.groupdocs.com/signature/net/electronic-signature-types/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced usage of creating various electronic signatures](https://docs.groupdocs.com/signature/net/signing/)

### See Also

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->