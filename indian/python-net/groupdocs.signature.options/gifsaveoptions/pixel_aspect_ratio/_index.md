---
title: "pixel_aspect_ratio प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "GIF पिक्सेल पहलू अनुपात।"
type: docs
url: /hi/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

GIF पिक्सेल पहलू अनुपात।

Pixel Aspect Ratio – मूल इमेज में पिक्सेल के अनुपात का अनुमान लगाने के लिए उपयोग किया जाने वाला कारक। यदि फ़ील्ड का मान 0 नहीं है, तो इस अनुपात का अनुमान निम्न सूत्र के आधार पर गणना किया जाता है:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

Pixel Aspect Ratio को पिक्सेल की चौड़ाई को उसकी ऊँचाई से विभाजित करने के रूप में परिभाषित किया गया है। इस फ़ील्ड में मान की सीमा 4:1 के सबसे चौड़े पिक्सेल से लेकर 1:4 के सबसे ऊँचे पिक्सेल तक 1/64वें भाग के अंतराल में निर्दिष्ट करने की अनुमति देती है।

मान:
- 0 – No aspect ratio information is given.
- 1..255 – Value used in the computation.

### Definition:
```python
@property
def pixel_aspect_ratio(self):
    ...
@pixel_aspect_ratio.setter
def pixel_aspect_ratio(self, value):
    ...
```

### संबंधित देखें
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
