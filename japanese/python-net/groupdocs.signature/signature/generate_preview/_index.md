---
title: "generate_preview メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントページのプレビューを生成します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

ドキュメントページのプレビューを生成します。

ドキュメントページのプレビューを生成する方法の詳細はこちら:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| preview_options | `PreviewOptions` | プレビューオプションです。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # ページ番号は 0 から始まります：preview_page_0.png が最初のページです
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

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
