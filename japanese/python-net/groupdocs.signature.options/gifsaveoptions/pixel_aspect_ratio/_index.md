---
title: "pixel_aspect_ratio プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "GIF のピクセルアスペクト比です。"
type: docs
url: /ja/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

GIF のピクセルアスペクト比です。

Pixel Aspect Ratio – 元画像のピクセルのアスペクト比の近似値を計算するために使用される係数です。フィールドの値が 0 でない場合、このアスペクト比の近似は以下の式に基づいて計算されます：

アスペクト比 = (Pixel Aspect Ratio + 15) / 64

Pixel Aspect Ratio は、ピクセルの幅を高さで割った商として定義されます。このフィールドの値範囲は、最も幅の広いピクセル 4:1 から最も高さの高いピクセル 1:4 まで、1/64 の刻みで指定できます。

値:
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

### 関連項目
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
