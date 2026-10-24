---
title: "BarcodeVerifyOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "バーコード検証オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---


## BarcodeVerifyOptions class

バーコード検証オプションを表します。

詳細を見る
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings

BarcodeVerifyOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/) | バーコード署名のデフォルト検証オプションを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text) | 検証テキストを使用したデフォルト検証オプションを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#encode_type) | バーコードタイプの検証を使用したデフォルト検証オプションを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text-encode_type) | バーコードタイプの検証とテキストを使用したデフォルト検証オプションを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type/) | 検証に使用されるバーコードタイプです。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 各ドキュメントページを検証するかどうかを示すフラグ。デフォルトは True です。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 代替署名オプション検証のための追加拡張子。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | 検証対象のフォームフィールドのタイトルです。設定した場合、テキストはテキストフォームフィールド内でのみ見つかります。 ([`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/) から継承) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | 検証対象のフォームフィールドのタイプです。設定した場合、テキストはテキストフォームフィールド内でのみ見つかります。 ([`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/) から継承) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有効なプロパティフラグ。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | テキスト一致タイプの検証です。 ([`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/) から継承) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 検証対象のドキュメントページ番号。設定されていない場合、ドキュメントのすべてのページが最初の出現箇所で検証されます（最小値は 1）。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 検証対象のページを指定するページオプションです。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | ヘッダー/フッターの署名を検証するために使用される文書レイアウト内のシェイプ位置です。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | 検証対象のテキスト署名 ID です。0 より大きい必要があり、PDF ドキュメントでのみサポートされます。 ([`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/) から継承) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | 検証対象の署名タイプです。 ([`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/) から継承) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | 検証対象の署名テキストです。 ([`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/) から継承) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import BarcodeVerifyOptions


def verify_barcode_signatures():
    with Signature("signed.pdf") as signature:
        options = BarcodeVerifyOptions()
        options.all_pages = True
        options.text = "12345"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document was verified successfully: {len(result.succeeded)} matching barcode signature(s).")
        else:
            print("Document failed verification process.")
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
