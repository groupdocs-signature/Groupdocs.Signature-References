---
title: "PdfMetadataSignatures クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PDF ドキュメントのメタデータ署名オプション用の標準メタデータ署名を含みます。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/pdfmetadatasignatures/
is_root: false
weight: 450
---


## PdfMetadataSignatures class

PDF ドキュメントのメタデータ署名オプション用の標準メタデータ署名を含みます。

PdfMetadataSignatures 型は次のメンバーを公開します:

### フィールド
| フィールド | 説明 |
| :- | :- |
| [AUTHOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/author/) | Pdf ドキュメント 作者 メタデータ。 |
| [CREATE_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/create_date/) | Pdf ドキュメント 作成日 メタデータ 署名。 |
| [METADATA_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/metadata_date/) | Pdf ドキュメント メタデータ 日付 情報。 |
| [CREATOR_TOOL](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator_tool/) | Pdf ドキュメント 作成ツール メタデータ 署名。 |
| [MODIFY_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/modify_date/) | Pdf ドキュメント 変更日 メタデータ プロパティ。 |
| [PRODUCER](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/producer/) | Pdf ドキュメント プロデューサー メタデータ プロパティ。 |
| [ENTRY](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/entry/) | Pdf ドキュメント エントリ メタデータ プロパティ。 |
| [KEYWORDS](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/keywords/) | Pdf ドキュメント クリエイター メタデータ プロパティ |
| [TITLE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/title/) | Pdf ドキュメント タイトル メタデータ プロパティ |
| [SUBJECT](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/subject/) | Pdf ドキュメント サブジェクト メタデータ プロパティ。 |
| [DESCRIPTION](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/description/) | Pdf ドキュメント 説明 メタデータ プロパティ。 |
| [CREATOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator/) | Pdf ドキュメント クリエイター メタデータ プロパティ。 |

### 例

```python
from datetime import datetime, timedelta

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures


def sign_pdf_standard():
    with Signature("sample.pdf") as signature:
        options = MetadataSignOptions()

        now = datetime.now()
        signatures = [
            PdfMetadataSignatures.AUTHOR.clone("Mr.Scherlock Holmes"),
            PdfMetadataSignatures.CREATE_DATE.clone(now - timedelta(days=1)),
            PdfMetadataSignatures.METADATA_DATE.clone(now - timedelta(days=2)),
            PdfMetadataSignatures.CREATOR_TOOL.clone("GD.Signature-Test"),
            PdfMetadataSignatures.MODIFY_DATE.clone(now - timedelta(days=13)),
            PdfMetadataSignatures.PRODUCER.clone("GroupDocs-Producer"),
            PdfMetadataSignatures.ENTRY.clone("Signature"),
            PdfMetadataSignatures.KEYWORDS.clone("GroupDocs, Signature, Metadata, Creation Tool"),
            PdfMetadataSignatures.TITLE.clone("Metadata Example"),
            PdfMetadataSignatures.SUBJECT.clone("Metadata Test Example"),
            PdfMetadataSignatures.DESCRIPTION.clone("Metadata Test example description"),
            PdfMetadataSignatures.CREATOR.clone("GroupDocs.Signature"),
        ]

        options.signatures.add_range(signatures)
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
