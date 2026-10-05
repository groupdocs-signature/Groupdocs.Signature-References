---
title: TextShadow class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents text shadow properties for text signatures."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/textshadow/
is_root: false
weight: 380
---


## TextShadow class

Represents text shadow properties for text signatures.

The result may vary depending on the signature type and document format.

TextShadow is recommended for use with `TextAsImage` signature for all supported document types, also with simple [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) and [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) as watermark for spreadsheets (`.xslx`) and presentations (`.pptx`).

Simple [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) for Word documents (`.docx`) is recommended too, but has limited functionality.

The TextShadow type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/__init__/) | Initializes TextShadow with default options. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Gets a copy of this object. (inherited from [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Properties
| Property | Description |
| :- | :- |
| [angle](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/angle/) | The angle for placing the shadow relative to the text. Default value is 0. |
| [blur](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/blur/) | The blur of the shadow. Default value is 4. |
| [color](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/color/) | The color of the shadow. Default value is Black. |
| [distance](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/distance/) | The distance from the text to the shadow. |
| [transparency](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/transparency/) | The transparency of the shadow. |

### See Also
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
