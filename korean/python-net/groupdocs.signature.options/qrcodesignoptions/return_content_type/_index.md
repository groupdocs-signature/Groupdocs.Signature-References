---
title: "return_content_type 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "returncontent 속성이 활성화된 경우 QR‑Code 서명의 반환된 이미지 내용의 파일 유형."
type: docs
url: /ko/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

`return_content` 속성이 활성화된 경우 QR‑Code 서명의 반환된 이미지 콘텐츠 파일 형식.

기본값은 `None`이며, 이는 [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/)에서 지정한 원래 형식으로 QR‑Code 이미지 내용을 반환합니다.

지원되는 값은 [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), 그리고 [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/)입니다. 지원되지 않는 형식이 제공될 경우, 내용은 PNG 형식으로 반환됩니다.

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
