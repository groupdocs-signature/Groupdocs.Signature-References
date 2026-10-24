---
title: "QrCodeSearchOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "QR コード署名の検索オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

QR コード署名の検索オプションを表します。

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

QrCodeSearchOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | QRCodeSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプの値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプとテキストの値で初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | QRコード署名のテキストまたはデータプロパティをエンコードおよびデコードするために使用される [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) の実装です。 |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | QRコードを検索するためのエンコードタイプです。 |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | 検索時に使用される QR-Code テキストマッチタイプです。 |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | ドキュメントページ上の各署名に対して QR‑Code 画像コンテンツを返すかどうかを決定するフラグです。True に設定すると、生の画像データが `return_content_type` で指定された形式で署名の `content` プロパティに保持されます。デフォルトでは無効です。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | `return_content` プロパティが有効な場合の QR-Code 署名の返却画像コンテンツのファイルタイプです。 |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | 検索およびマッチング対象の QR-Code 署名テキストです。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 各ドキュメントページで検索するかどうかを示すフラグです。デフォルトではこの値は True です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 検索対象のドキュメントページ番号（オプション）。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 署名検索の対象ページを指定するオプションです。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | ドキュメントレイアウト内のシェイプ位置を返すかどうかを示すフラグです。Word ドキュメントでのみ利用可能です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` とマークされた署名のみを返すフラグです。デフォルトでは値は `False` で、指定された条件に一致するすべての署名が返されることを示します。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
