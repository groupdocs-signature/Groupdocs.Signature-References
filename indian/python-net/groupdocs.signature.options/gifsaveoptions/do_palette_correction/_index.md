---
title: "do_palette_correction प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला फ़्लैग।"
type: docs
url: /hi/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला फ़्लैग।

Palette correction का अर्थ है कि जब भी इमेज को GIF में एक्सपोर्ट किया जाता है, स्रोत इमेज के रंगों का विश्लेषण किया जाता है ताकि सबसे उपयुक्त पैलेट बनाया जा सके (यदि इमेज पैलेट मौजूद नहीं है या विकल्पों में निर्दिष्ट नहीं है)। विश्लेषण प्रक्रिया में कुछ समय लगता है; हालांकि, आउटपुट इमेज में सबसे उपयुक्त रंग पैलेट होगा और परिणाम दृश्य रूप से बेहतर होगा।

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### संबंधित देखें
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
