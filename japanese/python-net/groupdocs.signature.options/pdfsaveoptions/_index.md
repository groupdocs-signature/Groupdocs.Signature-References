---
title: "PdfSaveOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PDF ドキュメントの保存オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

PDF ドキュメントの保存オプションを表します。

PdfSaveOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | デフォルト値で PdfSaveOptions の新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | 指定された出力ファイル形式で PdfSaveOptions の新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | 上書きフラグを使用して PdfSaveOptions の新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | 指定された出力ファイル形式と上書きフラグで PdfSaveOptions の新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | 署名されたドキュメントのファイル形式です。 |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | 印刷、変更、データ抽出などの PDF ドキュメント権限です。 |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | 権限設定を変更するために必要な権限パスワード（メインパスワード）です。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 出力ファイルパスに拡張子がない場合に自動的に追加するかどうかを決定するフラグです。デフォルト値は False です。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 既存のファイルを新しい出力ファイルで上書きするかどうかを示すフラグです。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 保存された署名ドキュメントを保護するために使用されるパスワードです。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 署名ドキュメントを保護された状態で保存する際に、[`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) のパスワードを使用するかどうかを示すフラグです。デフォルト値は True です。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
