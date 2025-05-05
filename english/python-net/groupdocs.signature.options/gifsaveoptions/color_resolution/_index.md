---
title: color_resolution property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 50
---

## color_resolution property


Gets or sets the GIF color resolution.

### Remarks 


Color Resolution - Number of bits per primary color available to the original
image, minus 1. This value represents the size of the entire palette from
which the colors in the graphic were selected, not the number of colors actually
used in the graphic.  For example, if the value in this field is 3, then
the palette of the original image had 4 bits per primary color available
to create the image. This value should be set to indicate the richness of
the original palette, even if not every color from the whole palette is available
on the source machine.
### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### See Also
* module [`groupdocs.signature.options`](../../)
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions)
