---
title: "return_content_type 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "returncontent 속성이 활성화된 경우 반환되는 이미지 콘텐츠의 파일 유형."
type: docs
url: /ko/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

return_content 속성이 활성화된 경우 반환되는 이미지 콘텐츠의 파일 형식.

설정되지 않은 경우(기본 `None`), 이미지 콘텐츠는 [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/)에 정의된 원래 형식으로 반환됩니다. 지원되는 값은 [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), 및 [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/)입니다. 지원되지 않는 형식을 제공하면 원래 형식이 반환됩니다.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### 또 보기
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
