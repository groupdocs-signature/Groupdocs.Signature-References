---
title: TextShadow class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/textshadow/
is_root: false
weight: 310
---

## TextShadow class

Represents text shadow properties for text signatures.
The result may vary depending on the signature type and document format.
TextShadow is recommended for using with TextAsImage signature for all supported document types,
also with simple TextSignature and TextSignature as watermark for Spreadsheets (.xslx) and Presentations (.pptx).
Simple TextSignature for Words (.docx) is recommended too, but has limited functionality.



**Inheritance:** [`TextShadow`](/signature/python-net/groupdocs.signature.domain.extensions/textshadow) → 
[`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension)



The TextShadow type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/__init__/#) | Creates TextShadow with default options. |


### Properties
| Property | Description |
| :- | :- |
| [distance](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/distance) | Gets or sets distance from text to shadow.<br/>Default value is 1. |
| [angle](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/angle) | Gets or sets angle for placing shadow relative to the text.<br/>Default value is 0. |
| [color](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/color) | Gets or sets color of the shadow.<br/>Default value is Black. |
| [transparency](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/transparency) | Gets or sets transparency of the shadow.<br/>Default value is 0. |
| [blur](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/blur) | Gets or sets blur of the shadow.<br/>Default value is 4. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/clone/#) | Gets a copy of this object. |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension)
* class [`TextShadow`](/signature/python-net/groupdocs.signature.domain.extensions/textshadow)
