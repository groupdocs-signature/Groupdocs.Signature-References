---
title: "MetadataSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名のプロパティです。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/metadatasignature/
is_root: false
weight: 360
---


## MetadataSignature class

メタデータ署名のプロパティです。

MetadataSignature 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/metadatasignature/clone/) | Metadata Signature インスタンスをクローンします。 |
| [clone](/signature/python-net/groupdocs.signature.domain/metadatasignature/clone/#value) | 指定された値で Metadata Signature インスタンスをクローンします。 |
| [clone_object](/signature/python-net/groupdocs.signature.domain/metadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals/#obj) | 指定された署名がこのインスタンスと等しいかどうかを判断します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_hash_code/) | メタデータ署名のハッシュコードを返します。 |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_boolean/) | ブール値に変換します。 |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/) | メタデータ署名の値を datetime に変換します。 |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/#provider) | メタデータ署名の値を datetime に変換します。 |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/) | メタデータ署名の値を Decimal に変換します。 |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/#provider) | メタデータ署名の値を Decimal に変換します。 |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/) | メタデータ署名の値を float に変換します。 |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/#provider) | Double に変換します。 |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_integer/) | メタデータ署名の値を整数に変換します。 |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/) | メタデータ署名の値を float に変換します。 |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/#provider) | float に変換します。 |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string/) | メタデータ署名を文字列に変換します。 |
| [to_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string/#format) | 指定された形式を使用してメタデータ署名を文字列に変換します。 |
| [to_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string/#format-provider) | 指定された形式で文字列に変換します。 |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_string/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | 署名値プロパティをエンコードおよびデコードするために使用される [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) の実装です。 |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | 一意のメタデータ名です。 |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | メタデータの値タイプです。 |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | メタデータオブジェクトです。 |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 署名の作成日です。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | この署名がドキュメントから削除されたかどうかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 署名の高さです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | このコンポーネントが署名 (`True`) かドキュメントコンテンツ (`False`) のどちらを表すかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 署名の左側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 署名の変更日です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 署名が見つかったページ番号です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 署名の一意の識別子です。更新または削除操作でドキュメント内の署名を変更するために使用されます。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 署名のタイプです。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 署名の上側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 署名の幅です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value} ({metadata.type.name})")
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
