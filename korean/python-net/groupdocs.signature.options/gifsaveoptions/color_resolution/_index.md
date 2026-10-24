---
title: "color_resolution 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "GIF 색 해상도."
type: docs
url: /ko/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

GIF 색 해상도.

Color Resolution - 원본 이미지에서 사용할 수 있는 기본 색당 비트 수에서 1을 뺀 값입니다. 이 값은 그래픽에서 선택된 색상이 아닌 전체 팔레트의 크기를 나타냅니다. 예를 들어, 이 필드의 값이 3이면 원본 이미지의 팔레트는 이미지 생성에 사용할 수 있는 기본 색당 4비트를 가지고 있음을 의미합니다. 이 값은 전체 팔레트의 모든 색상이 소스 머신에 존재하지 않더라도 원본 팔레트의 풍부함을 나타내도록 설정해야 합니다.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### 또 보기
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
