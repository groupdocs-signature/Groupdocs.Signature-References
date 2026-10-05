---
title: do_palette_correction property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag indicating whether palette correction is applied."
type: docs
url: /python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

The flag indicating whether palette correction is applied.

Palette correction means that whenever an image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case the image palette does not exist or is not specified in the options). The analysis process takes some time; however, the output image will have the best matching color palette and the result is visually better.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### See Also
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
