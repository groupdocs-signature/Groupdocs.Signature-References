---
title: TextSignatureImplementation
second_title: GroupDocs.Signature for .NET API Reference
description: Specifies type of implementation for PDF text signature.
type: docs
weight: 970
url: /net/groupdocs.signature.domain/textsignatureimplementation/
---
## TextSignatureImplementation enumeration

Specifies type of implementation for PDF text signature.

```csharp
public enum TextSignatureImplementation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Native | `1` | Text Signature as native text object on document page. |
| Image | `2` | Text Signature as Image object on document page. |
| Annotation | `3` | Text Signature as Text Annotation object on PDF page. Annotations are visible only for Licensed version. |
| Sticker | `4` | Text Signature as Sticker object on PDF page. |
| FormField | `5` | Text Signature as text in specified form field. With this type of implementation could be used only TextSignOptions.Text, TextSignOptions.FormTextFieldType and TextSignOptions.FormTextFieldTitle options. |
| Watermark | `6` | Text Signature as watermark on document page. |

### See Also

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->