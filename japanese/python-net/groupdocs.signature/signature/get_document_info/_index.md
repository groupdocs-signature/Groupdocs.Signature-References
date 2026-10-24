---
title: "get_document_info メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントページに関する情報を取得します：サイズ、最大ページ高さ、最大高さのページの幅。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

ドキュメントページに関する情報を取得します：サイズ、最大ページ高さ、最大高さのページの幅。

署名済みドキュメントの詳細 - ファイルタイプ、ページ数、その他多数のフォーマット固有プロパティについて学ぶ:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### 例

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number は 0 ベースです: 0 が最初のページです
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
