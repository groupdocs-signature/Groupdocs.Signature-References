---
title: "DigitalSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "このクラスはデジタル署名のプロパティを含みます。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

このクラスはデジタル署名のプロパティを含みます。

DigitalSignature 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | デフォルトパラメータでデジタル署名を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | 既知の署名識別子でデジタル署名を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | 指定された X509 ストアの最初の証明書を使用して DigitalSignature を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | 指定された X509 ストアと証明書インデックスに基づいて DigitalSignature を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | 指定された証明書でデジタル署名を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | バーコード署名インスタンスをクローンします。 |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | この署名と別の署名を等価性で比較します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | デジタル署名のハッシュコードを返します。 |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | すべてのシステム X509 証明書ストアからデジタル署名をロードします。 |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | 証明書ストレージからデジタル署名をロードします。 |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | 証明書ストレージからデジタル署名をロードします。 |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | 特定の場所に配置されたデジタル証明書ストレージからデジタル署名をロードします。 |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | 特定の場所に配置されたデジタル証明書ストレージからデジタル署名をロードします。 |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | デジタル署名に関連付けられた X509 証明書です。 |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | 証明書のカスタムストア名です。 |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | 証明書のストア場所です。 |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | 証明書のストア名です。 |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | 署名目的のコメントです。 |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | デジタル署名は有効で、ドキュメントは改ざんされていません。 |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | ドキュメントが署名された時刻です。 |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | 証明書のサムプリントです。 |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | XAdES のタイプ ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
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
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
