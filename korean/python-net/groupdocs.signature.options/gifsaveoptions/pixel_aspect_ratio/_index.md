---
title: "pixel_aspect_ratio 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "GIF 픽셀 종횡비입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

GIF 픽셀 종횡비입니다.

Pixel Aspect Ratio – 원본 이미지에서 픽셀의 종횡비 근사값을 계산하는 데 사용되는 요소입니다. 필드 값이 0이 아니면, 이 종횡비 근사는 다음 공식에 따라 계산됩니다:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

Pixel Aspect Ratio는 픽셀의 너비를 높이로 나눈 값으로 정의됩니다. 이 필드의 값 범위는 4:1의 가장 넓은 픽셀부터 1:4의 가장 높은 픽셀까지 1/64 단위로 지정할 수 있습니다.

값:
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

### 또 보기
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
