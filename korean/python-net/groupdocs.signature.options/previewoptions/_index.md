---
title: "PreviewOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서 미리보기 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

문서 미리보기 옵션을 나타냅니다.

PreviewOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | 미리보기 이미지 높이. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | 페이지 미리보기 이미지에서 서명이 숨겨져 있는지 여부를 나타내는 플래그. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | 미리보기 이미지 페이지 번호. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | 미리보기 이미지 형식. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | 미리보기 이미지의 해상도(DPI, 인치당 점). 기본 해상도는 96 DPI입니다. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | 미리보기 이미지 너비. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

with Signature("sample.pdf") as signature:
    preview_options = PreviewOptions(create_page_stream)
    preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
    signature.generate_preview(preview_options)
```

### Guides
`PreviewOptions`를 사용하는 작업 가이드:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
