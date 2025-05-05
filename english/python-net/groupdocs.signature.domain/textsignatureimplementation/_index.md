---
title: TextSignatureImplementation enumeration
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/textsignatureimplementation/
is_root: false
weight: 810
---

## TextSignatureImplementation enumeration

Specifies type of implementation for PDF text signature.



The TextSignatureImplementation type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NATIVE | Text Signature as native text object on document page. |
| IMAGE | Text Signature as Image object on document page. |
| ANNOTATION | Text Signature as Text Annotation object on PDF page.<br/>Annotations are visible only for Licensed version. |
| STICKER | Text Signature as Sticker object on PDF page. |
| FORM_FIELD | Text Signature as text in specified form field.<br/>With this type of implementation could be used only TextSignOptions.Text, <br/>TextSignOptions.FormTextFieldType and TextSignOptions.FormTextFieldTitle options. |
| WATERMARK | Text Signature as watermark on document page. |



### See Also
* module [`groupdocs.signature.domain`](..)
