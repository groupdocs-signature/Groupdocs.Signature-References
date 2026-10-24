---
title: "SignatureSettings クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "Signature の動作をカスタマイズするための設定を表します。"
type: docs
url: /ja/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

[`Signature`](/signature/python-net/groupdocs.signature/signature/) の動作をカスタマイズする設定を表します。

SignatureSettings 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | デフォルト値でデフォルトの SignatureSettings インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Logger 実装を使用してデフォルトの SignatureSettings インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | ドキュメント処理中に使用されるデフォルトのカルチャです。デフォルト値は "en-US" です。 |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | 標準ドキュメントメタデータ署名（Author、Owner、作成日、変更日など）がメタデータリストに含まれるかどうかを示すフラグです。 |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | どの種類のメッセージが [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) に渡されるかを決定するログレベルフラグです。 |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | ロギング（Errors、Warnings、Traces）に使用されるロガー実装です。 [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/)。 |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Delete メソッドで影響を受ける署名が削除されない場合に、ソースドキュメントを再保存するかどうかを決定するフラグです。 |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | `Update` メソッドで更新する署名がない場合に、ソースドキュメントを再保存するかどうかを決定するフラグです。 |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | 削除された署名がドキュメント情報の結果に含まれるかどうかを決定するフラグです。各 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) には、削除されたかどうかを示す `Deleted` フラグがあります。 |

### 関連項目
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
