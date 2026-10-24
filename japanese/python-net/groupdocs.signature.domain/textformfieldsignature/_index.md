---
title: "TextFormFieldSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PDF ドキュメント用のテキスト入力フォームフィールド署名プロパティを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

PDF ドキュメント用のテキスト入力フォームフィールド署名プロパティを表します。

TextFormFieldSignature 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | 事前定義された名前で PdfTextFormFieldSignature を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | 事前定義された名前で PdfTextFormFieldSignature を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | FormField Signature インスタンスをクローンします。 |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | 型とプロパティ値に基づき、この署名と別の署名を等価かどうか比較します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | GetHashCode メソッドをオーバーライドします。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | フォームフィールド入力のテキスト。 |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 署名の作成日です。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | この署名がドキュメントから削除されたかどうかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 署名の高さです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | このコンポーネントが署名 (`True`) かドキュメントコンテンツ (`False`) のどちらを表すかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 署名の左側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 署名の変更日です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | 一意のフォームフィールド名です。（[`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/) から継承） |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 署名が見つかったページ番号です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 署名の一意の識別子です。更新または削除操作でドキュメント内の署名を変更するために使用されます。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 署名のタイプです。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 署名の上側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | フォームフィールドのタイプです。（[`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/) から継承） |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | フォームフィールドのデータオブジェクトです。（[`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/) から継承） |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 署名の幅です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # 名前が "FieldText" で値が "Value1" のテキスト フィールドを作成します
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # それのフォームフィールドオプションを作成する
        options = FormFieldSignOptions(text_field)

        # フォームフィールドの位置とサイズを設定する
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # ドキュメントに署名し、結果を保存する
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
