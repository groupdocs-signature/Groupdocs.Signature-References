---
title: "ExportImageSaveOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントを画像にエクスポートするための保存オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

ドキュメントを画像にエクスポートするための保存オプションを表します。

ExportImageSaveOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | ExportAsImageSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | 指定されたファイル形式で ExportAsImageSaveOptions の新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | 画像の境界設定です。デフォルトではこの値は設定されていません。 |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | 各ページをエクスポートするフラグです。 |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | エクスポートされた画像の列数です。画像を横に並べる必要がある場合はこのプロパティを使用してください。 |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | エクスポート対象の文書ページ番号です（最小値は1）。 |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | 署名対象ページを指定するオプション。 |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | 文書ページはTIFF画像の異なるフレームに配置されます。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 出力ファイルパスに拡張子がない場合に自動的に追加するかどうかを決定するフラグです。デフォルト値は False です。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 署名済みドキュメントのファイル形式です。(継承元: [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 既存のファイルを新しい出力ファイルで上書きするかどうかを示すフラグです。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 保存された署名ドキュメントを保護するために使用されるパスワードです。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 署名ドキュメントを保護された状態で保存する際に、[`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) のパスワードを使用するかどうかを示すフラグです。デフォルト値は True です。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
