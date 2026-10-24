---
title: "TextSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "TextSignature クラスはテキスト署名プロパティを含みます。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

TextSignature クラスはテキスト署名プロパティを含みます。

TextSignature 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | 署名または検索操作で取得したユニークな署名識別子を使用して TextSignature オブジェクトを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Text Signature インスタンスをクローンします。 |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | 指定された署名とこのインスタンスを等価かどうか比較します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | 署名のハッシュコードを返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | 署名がドキュメント固有かどうかを示すネイティブ属性です。 |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | テキスト署名の実装。 |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | 署名のテキスト。 |
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
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
