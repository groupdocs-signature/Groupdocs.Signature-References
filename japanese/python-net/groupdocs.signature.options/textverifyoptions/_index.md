---
title: "TextVerifyOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントのテキスト署名を検証するオプションを保持します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

ドキュメントのテキスト署名を検証するオプションを保持します。

詳しくは以下をご覧ください:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

TextVerifyOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | `TextVerifyOptions` の新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | `TextVerifyOptions` の新しいインスタンスを検証テキストで初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | 検証するテキストと署名実装タイプを指定して、新しい TextVerifyOptions インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | 検証対象のフォームフィールドのタイトル。設定すると、テキストはテキストフォームフィールド内でのみ検索されます。 |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | 検証対象のフォームフィールドのタイプ。設定すると、テキストはテキストフォームフィールド内でのみ検索されます。 |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | テキスト一致タイプの検証。 |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | 検証するテキスト署名 ID。0 より大きい必要があり、PDF ドキュメントでのみサポートされます。 |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | 検証対象の署名タイプ。 |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | 検証する署名テキスト。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 各ドキュメントページを検証するかどうかを示すフラグ。デフォルトは True です。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 代替署名オプション検証のための追加拡張子。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有効なプロパティフラグ。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 検証対象のドキュメントページ番号。設定されていない場合、ドキュメントのすべてのページが最初の出現箇所で検証されます（最小値は 1）。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 検証対象のページを指定するページオプションです。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | ヘッダー/フッターの署名を検証するために使用される文書レイアウト内のシェイプ位置です。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
`TextVerifyOptions` を使用するタスク ガイド：

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
