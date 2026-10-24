---
title: "ImageMetadataSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "画像メタデータ署名を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

画像メタデータ署名を表します。

画像ドキュメントのメタデータ署名は、EXIF などの画像メタデータ標準に基づく電子署名です。各署名は数値識別子 (0‑65535) で識別され、さまざまなタイプ（テキスト、日付/時刻、整数、浮動小数点）の値を格納します。

ImageMetadataSignature 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | 指定された識別子と値で画像メタデータ署名を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | メタデータ署名インスタンスをクローンします。 |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | 指定された値で ImageMetadataSignature インスタンスをクローンします。 |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | 指定された署名オブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | 署名のハッシュコードを返します。 |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | メタデータ署名の値をブール値に変換します。 |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | メタデータ署名の値を `datetime.datetime` に変換します。 |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | メタデータ署名の値を `datetime` に変換します。 |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Decimal に変換します。 |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | メタデータ署名の値を decimal に変換します。 |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | float に変換します。 |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | メタデータ署名の値を float に変換します。 |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | メタデータ署名の値を整数に変換します。 |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | long に変換します。 |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | float に変換します。 |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | メタデータ署名の値を float に変換します。 |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | メタデータ署名の値を文字列に変換します。 |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | 指定された形式を使用してメタデータ署名の値を文字列に変換します。 |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | 指定された形式で文字列に変換します。 |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | ([`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/) から継承) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | 標準の画像メタデータ署名の説明です。 |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | 画像メタデータ署名の識別子です。事前定義された Id 値を持つ標準署名を含む `GroupDocs.Signature.Domain.ImageMetadataSignatures` クラスをご覧ください。 |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | メタデータ値のサイズです。 |
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
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
