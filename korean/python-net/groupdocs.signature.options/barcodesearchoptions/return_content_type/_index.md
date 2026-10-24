---
title: "return_content_type 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "returncontent 속성이 활성화된 경우 바코드 서명에 대한 반환 이미지 내용의 파일 유형."
type: docs
url: /ko/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

`return_content` 속성이 활성화된 경우 바코드 서명의 반환된 이미지 콘텐츠 파일 유형입니다.

기본값은 None이며, 이는 [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) 에 지정된 원래 형식으로 바코드 이미지를 반환합니다.

지원되는 값은 [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), 그리고 [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) 입니다. 이들 외의 값이 제공되면 이미지는 PNG 형식으로 반환됩니다.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
