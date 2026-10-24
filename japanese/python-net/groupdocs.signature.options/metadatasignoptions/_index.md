---
title: "MetadataSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

メタデータ署名オプションを表します。

詳細を見る

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

MetadataSignOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | デフォルト値で MetadataSignOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) の新しいインスタンスをメタデータで初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | 既存の MetadataSignature インスタンスをコレクションに追加します。 |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | 指定された引数で新しい ImageMetadataSignature を作成し、コレクションに追加します。 |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | 指定された引数で新しい PdfMetadataSignature を作成し、コレクションに追加します。 |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) の実装は、このオプションコレクション内のすべてのメタデータ署名を暗号化するために使用されます。 |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | 署名に関連付けられたメタデータ署名です。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 署名はすべてのドキュメントページに配置されます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 追加の署名外観。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 署名オプションのドキュメントタイプ（`DocumentType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 署名拡張子。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 暗号操作に使用されるハッシュアルゴリズム。PDF ファイルのデジタル署名でのみサポートされます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 署名対象のドキュメントページ番号。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 署名対象ページを指定するオプション。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 署名タイプ（`SignatureType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | テキスト署名の Z 順序位置。重なり合う署名の表示順序を決定します。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |

### 例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
