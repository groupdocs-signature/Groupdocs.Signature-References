---
title: "BarcodeSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "バーコード署名を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/barcodesignature/
is_root: false
weight: 20
---


## BarcodeSignature class

バーコード署名を表します。

BarcodeSignature 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/barcodesignature/__init__/#signature_id) | 検索プロセス後に取得した署名識別子で BarcodeSignature オブジェクトを初期化します。識別子は、ドキュメントの署名情報レイヤーからこの署名の追加プロパティを取得するために使用されます。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/barcodesignature/clone/) | Barcode Signature インスタンスをクローンします。 |
| [equals](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals/#obj) | このバーコード署名と別の署名を等価性で比較します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/barcodesignature/get_hash_code/) | バーコード署名のハッシュコードを返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/barcodesignature/content/) | バーコードのバイナリデータ画像コンテンツは、[`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) で指定された形式です。 |
| [encode_type](/signature/python-net/groupdocs.signature.domain/barcodesignature/encode_type/) | バーコードのエンコードタイプ。 |
| [format](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) | バーコード署名画像の形式。 |
| [text](/signature/python-net/groupdocs.signature.domain/barcodesignature/text/) | バーコードのテキスト。 |
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

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
