---
title: "DigitalVBA クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "スプレッドシートのVBAプロジェクト用デジタル署名を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

スプレッドシートのVBAプロジェクト用デジタル署名を表します。

`Xlsm` や `Xltm` などのスプレッドシートドキュメント形式で VBA プロジェクトに署名する機能を提供します。複数の [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) 拡張機能が [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/) に追加された場合、署名時には最初のものだけが使用されます。

DigitalVBA 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | 証明書ファイルで DigitalVBA クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | 証明書ストリームで DigitalVBA クラスの新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | このオブジェクトのコピーを取得します。（[`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/) から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | デジタル証明書ファイルパスで、`CertificateStream` が指定されていない場合にのみ使用されます。 |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | デジタル証明書ストリームです。このプロパティが指定されている場合、常に CertificateFilePath の代わりに使用されます。 |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | 署名コメントです。 |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | デジタル証明書のパスワードです。 |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | VBA プロジェクトのみを署名するかどうかを決定する設定です。True の場合、スプレッドシートドキュメント自体は署名されず、VBA プロジェクトのみが署名されます。 |

### 例

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # スプレッドシート内のマクロに署名する
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # VBA プロジェクトにデジタル署名する拡張機能を追加する
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # VBA プロジェクトの署名パートが追加されたことを検証する
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### 関連項目
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
