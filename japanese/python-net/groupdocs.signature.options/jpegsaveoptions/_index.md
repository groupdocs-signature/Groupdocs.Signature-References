---
title: "JpegSaveOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "画像ドキュメントの JPEG 保存オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

画像ドキュメントの JPEG 保存オプションを表します。

JpegSaveOptions 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | JpegSaveOptions をデフォルト値で初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | ロスレス JPEG 画像のチャンネルあたりビット数。サポートされる値は 2 から 8 ビットです。 |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | JPEG 画像のカラ―タイプ。 |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | JPEG ファイルのコメント。 |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | 圧縮タイプ。 |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | 画像品質。 |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | `JpegOptions.BitsPerChannel` の n ビット値に 8 ビット値を合わせるために使用されるサンプル丸めモード。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 出力ファイルパスに拡張子がない場合に自動的に追加するかどうかを決定するフラグです。デフォルト値は False です。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 署名済みドキュメントのファイル形式です。(継承元: [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 既存のファイルを新しい出力ファイルで上書きするかどうかを示すフラグです。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 保存された署名ドキュメントを保護するために使用されるパスワードです。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 署名ドキュメントを保護された状態で保存する際に、[`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) のパスワードを使用するかどうかを示すフラグです。デフォルト値は True です。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
