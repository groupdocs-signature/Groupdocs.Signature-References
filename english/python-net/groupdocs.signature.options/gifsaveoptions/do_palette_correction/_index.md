---
title: do_palette_correction property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 60
---

## do_palette_correction property


Gets or sets a value indicating whether palette correction is applied.

### Remarks 


Palette correction means that whenever image is exported to GIF the source
image colors will be analyzed in order to build the best matching palette
(in case image Palette does not exist or not specified in the options). 
The analyze process takes some time however the output image will have the
best matching color palette and result is visually better.
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
* module [`groupdocs.signature.options`](../../)
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions)
