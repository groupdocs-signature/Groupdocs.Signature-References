---
title: "BmpSaveOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "画像ドキュメントの BMP 保存オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

画像ドキュメントの BMP 保存オプションを表します。

BmpSaveOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | BmpSaveOptions をデフォルト値で初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | 画像のピクセルあたりのビット数です。 |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | 圧縮です。`BitmapCompression` を参照してください。 |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | 水平解像度です。丸めの影響により、結果の解像度が設定値とわずかに異なる場合があります。 |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | 垂直解像度です。丸めの影響により、結果の解像度が設定値とわずかに異なる場合があります。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 出力ファイルパスに拡張子がない場合に自動的に追加するかどうかを決定するフラグです。デフォルト値は False です。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 署名済みドキュメントのファイル形式です。(継承元: [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 既存のファイルを新しい出力ファイルで上書きするかどうかを示すフラグです。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 保存された署名ドキュメントを保護するために使用されるパスワードです。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 署名ドキュメントを保護された状態で保存する際に、[`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) のパスワードを使用するかどうかを示すフラグです。デフォルト値は True です。Image ドキュメントではサポートされていません。(継承元: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
