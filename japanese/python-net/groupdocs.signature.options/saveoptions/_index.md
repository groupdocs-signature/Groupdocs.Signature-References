---
title: "SaveOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "署名用にドキュメントを保存する際に、追加オプション（パスワードなど）を指定します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

署名用にドキュメントを保存する際に、追加オプション（パスワードなど）を指定します。

SaveOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | デフォルト値で SaveOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | 指定された出力タイプと上書きフラグで SaveOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 出力ファイルパスに拡張子がない場合に自動的に追加するかどうかを決定するフラグです。デフォルト値は False です。 |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 既存のファイルを新しい出力ファイルで上書きするかどうかを示すフラグです。 |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 保存された署名済みドキュメントを保護するために使用されるパスワードです。Image ドキュメントではサポートされていません。 |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 署名済みドキュメントを保護された状態で保存する際に、[`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) のパスワードを使用するかどうかを示すフラグです。デフォルト値は True です。Image ドキュメントではサポートされていません。 |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
