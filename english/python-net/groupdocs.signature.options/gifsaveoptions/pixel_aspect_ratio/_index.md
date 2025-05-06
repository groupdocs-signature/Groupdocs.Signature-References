---
title: pixel_aspect_ratio property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 130
---

## pixel_aspect_ratio property


Gets or sets the GIF pixel aspect ratio.

### Remarks 


Pixel Aspect Ratio - Factor used to compute an approximation of the aspect
ratio of the pixel in the original image. If the value of the field is not
0, this approximation of the aspect ratio is computed based on the formula:
Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined
to be the quotient of the pixel's width over its height. The value range
in this field allows specification of the widest pixel of 4:1 to the tallest
pixel of 1:4 in increments of 1/64th.  Values : 0 - No aspect ratio information
is given.  1..255 - Value used in the computation.
### Definition:
```python
@property
def pixel_aspect_ratio(self):
    ...
@pixel_aspect_ratio.setter
def pixel_aspect_ratio(self, value):
    ...
```

### See Also
* module [`groupdocs.signature.options`](../../)
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions)
