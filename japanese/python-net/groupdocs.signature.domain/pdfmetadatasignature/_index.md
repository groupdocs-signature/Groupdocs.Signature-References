---
title: "PdfMetadataSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PDF メタデータ署名を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/pdfmetadatasignature/
is_root: false
weight: 440
---


## PdfMetadataSignature class

PDF メタデータ署名を表します。

PdfMetadataSignature 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name) | 事前定義された名前と空の値で PDF メタデータ署名を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value) | 事前定義された値で PDF メタデータ署名を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value-tag) | 事前定義された値で PDF メタデータ署名を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/) | メタデータ署名インスタンスをクローンします。 |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/#value) | 指定された値で PDF メタデータ署名インスタンスをクローンします。 |
| [clone_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals/#obj) | この署名を他の署名とプロパティに基づいて等価かどうか比較します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/get_hash_code/) | 署名のハッシュコードを返します。 |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_boolean/) | ブール値に変換します。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/) | メタデータ署名の値を datetime に変換します。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time_iformat_provider/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/) | メタデータ署名の値を Decimal に変換します。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal_iformat_provider/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/) | メタデータ署名の値を float に変換します。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double_iformat_provider/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_integer](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_integer/) | メタデータ署名の値を integer に変換します。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/) | メタデータ署名の値を float に変換します。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single_iformat_provider/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string/) | メタデータ署名を文字列に変換します。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_file/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_string/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [tag_prefix](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/tag_prefix/) | PDF メタデータ署名名のプレフィックスタグです。デフォルトではこのプロパティは "xmp" に設定されています。 |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 署名の作成日です。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | 署名値プロパティのエンコードとデコードに使用される [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) の実装です。 ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | この署名がドキュメントから削除されたかどうかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 署名の高さです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | このコンポーネントが署名 (`True`) かドキュメントコンテンツ (`False`) のどちらを表すかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 署名の左側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 署名の変更日です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | 一意のメタデータ名です。 (継承元: [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 署名が見つかったページ番号です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 署名の一意の識別子です。更新または削除操作でドキュメント内の署名を変更するために使用されます。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 署名のタイプです。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 署名の上側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | メタデータの値タイプです。 (継承元: [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | メタデータオブジェクトです。 (継承元: [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 署名の幅です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### 例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
