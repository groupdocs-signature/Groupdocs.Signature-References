---
title: "skip_external_resources プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントが外部リソースをロードするのを停止するフラグ。"
type: docs
url: /ja/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

ドキュメントが外部リソースをロードするのを停止するフラグです。デフォルト値は True で、[`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) と一致するものを除き、外部リソースはロードされません。

ドキュメントは、リンクされた画像や INCLUDEPICTURE フィールドで挿入された画像、プレゼンテーションやスプレッドシート内のリンク画像、SVG 画像で参照される画像やスタイルシートなど、外部に保存されたリソースを参照できます。そのようなリソースをロードすると、ライブラリはそのアドレスにリクエストを送ります。信頼できないドキュメントを処理するサーバー上では、ドキュメントがこれを利用してサーバーに内部アドレスへのリクエスト（サーバーサイドリクエストフォージェリ）を送らせたり、UNC や `file://` パスが Windows にアカウントの NTLM 資格情報を別のホストへ送信させる可能性があります。オフラインまたはエアギャップ環境では、リクエストは失敗するかタイムアウトを待ちます。

スキップされたリソースはページプレビューや画像として保存されたドキュメントに描画されず、画像、バーコード、QR‑コードの検索でも検出されません。このプロパティは信頼できるドキュメントに対してのみ False に設定し、特定のアドレスを許可する場合は [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) を使用することを推奨します。

この設定はワードプロセッシング文書、プレゼンテーション、スプレッドシート、SVG 画像（アーカイブ内の文書を含む）に適用されます。SVG 画像の場合、許可されていない参照は読み込む前に画像から除去され、XML が正しく構成されていない SVG 画像は拒否されます。この設定は証明書失効チェック、タイムスタンプサーバー、ライセンスの管理を制御しません。

このプロパティは、意味が逆の [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) を置き換えます。

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### 関連項目
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
