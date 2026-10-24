---
title: "do_palette_correction 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "팔레트 보정이 적용되는지 여부를 나타내는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

팔레트 보정이 적용되는지 여부를 나타내는 플래그입니다.

Palette correction은 이미지가 GIF로 내보내질 때마다 소스 이미지 색상을 분석하여 최적의 팔레트를 구축한다는 의미입니다(이미지 팔레트가 없거나 옵션에 지정되지 않은 경우). 분석 과정에는 시간이 소요되지만, 출력 이미지가 최적의 색상 팔레트를 갖게 되어 시각적으로 더 나은 결과를 제공합니다.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### 또 보기
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
