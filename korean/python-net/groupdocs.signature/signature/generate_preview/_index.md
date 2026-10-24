---
title: "generate_preview 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서 페이지 미리보기를 생성합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

문서 페이지 미리보기를 생성합니다.

문서 페이지에 대한 미리보기를 생성하는 방법에 대해 자세히 알아보세요:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| preview_options | `PreviewOptions` | 미리보기 옵션. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # 페이지 번호는 0부터 시작합니다: preview_page_0.png가 첫 페이지입니다
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
