---
title: "PreviewOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントプレビューオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

ドキュメントプレビューオプションを表します。

PreviewOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | プレビュー画像の高さです。 |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | 署名がページプレビュー画像から非表示にされるかどうかを示すフラグです。 |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | プレビュー画像のページ番号です。 |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | プレビュー画像のフォーマットです。 |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | プレビュー画像の解像度（DPI、ドット毎インチ）です。デフォルトの解像度は 96 DPI です。 |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | プレビュー画像の幅です。 |

### 例

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
`PreviewOptions` を使用するタスクガイド:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
