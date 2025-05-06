---
title: JpegCompressionMode enumeration
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/jpegcompressionmode/
is_root: false
weight: 520
---

## JpegCompressionMode enumeration

Specifies JPEG compression modes.



The JpegCompressionMode type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| BASELINE | The baseline compression. |
| PROGRESSIVE | The progressive compression. |
| LOSSLESS | The lossless compression. Use this compression type carefully because <br/>many image viewers do not support it. If you use it try assign the <br/>[`JpegSaveOptions.color_type`](/signature/python-net/groupdocs.signature.options/jpegsaveoptions#color_type) property to [`JpegCompressionColorMode.GRAYSCALE`](/signature/python-net/groupdocs.signature.options/jpegcompressioncolormode#GRAYSCALE) <br/>or [`JpegCompressionColorMode.RGB`](/signature/python-net/groupdocs.signature.options/jpegcompressioncolormode#RGB) values. |
| JPEG_LS | The JPEG-LS compression. Use this compression type carefully because <br/>many image viewers do not support it. If you use it try to assign the <br/>[`JpegSaveOptions.color_type`](/signature/python-net/groupdocs.signature.options/jpegsaveoptions#color_type) property to [`JpegCompressionColorMode.GRAYSCALE`](/signature/python-net/groupdocs.signature.options/jpegcompressioncolormode#GRAYSCALE) <br/>value. |



### See Also
* module [`groupdocs.signature.options`](..)
