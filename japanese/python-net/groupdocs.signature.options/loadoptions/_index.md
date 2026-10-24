---
title: "LoadOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "LoadOptions クラスは、署名用にドキュメントを開く際に追加オプション（パスワードなど）を指定できるようにします。"
type: docs
url: /ja/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

LoadOptions クラスは、署名用にドキュメントを開く際に追加オプション（パスワードなど）を指定できるようにします。

ファイルが暗号化されている場合、`password` 属性をドキュメントのパスワードに設定します。

LoadOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | LoadOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | 指定されたファイルタイプで [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | ロードオプションに関連付けられたファイルタイプで、デフォルトは [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/) です。 |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | ドキュメントが外部リソースをロードするかどうかを決定するフラグです。このプロパティは廃止予定です。代わりに逆の意味を持つ [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) を使用してください。 |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | 保護されたドキュメントを開くため、また署名されたドキュメントを保護された状態で保存するために使用されるパスワードです。 |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | 印刷、変更、データ抽出などの PDF ドキュメント権限です。PDF ドキュメントにのみ適用されます。 |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | ドキュメントが外部リソースをロードするのを停止するフラグです。デフォルト値は True で、[`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) と一致するものを除き、外部リソースはロードされません。 |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) が true の場合でもロードされる外部リソースのアドレスフラグメントのリストです。デフォルト値は空のリストです。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
