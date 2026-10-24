---
title: "ImageSaveOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "画像ドキュメントの保存オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagesaveoptions/
is_root: false
weight: 230
---


## ImageSaveOptions class

画像ドキュメントの保存オプションを表します。

ImageSaveOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/) | デフォルト値で ImagesSaveOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#overwrite_existing_file) | 上書きフラグ付きで ImagesSaveOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#file_format-overwrite_existing_file) | 指定された出力ファイル形式と上書きフラグで ImagesSaveOptions の新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 署名されたドキュメントのファイル形式です。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 出力ファイルパスに拡張子がない場合に自動的に追加するかどうかを決定するフラグです。デフォルト値は False です。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 既存のファイルを新しい出力ファイルで上書きするかどうかを示すフラグです。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 保存された署名ドキュメントを保護するために使用されるパスワードです。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 署名ドキュメントを保護された状態で保存する際に、[`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) のパスワードを使用するかどうかを示すフラグです。デフォルト値は True です。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
