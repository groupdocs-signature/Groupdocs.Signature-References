---
title: "ImageDigitalVerifyOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ラスタ画像内のデジタル署名を検証するオプションを保持します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

ラスタ画像内のデジタル署名を検証するオプションを保持します。

ImageDigitalVerifyOptions 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | ラスタ画像内のデジタル（ステガノグラフィ）署名を検証するために ImageDigitalVerifyOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | AnalyzePercentageDigitalSignature が返す確率（0〜100）。 |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | 部分抽出の検出閾値パーセンテージ（0〜100）。デフォルトは 75 です。 |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | 署名を埋め込む際に使用されたパスワード。 |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | このプロパティは、最大精度のために完全データ抽出（AnalyzePercentageDigitalSignature）を実行するかどうかを決定します。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 各ドキュメントページを検証するかどうかを示すフラグ。デフォルトは True です。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 代替署名オプション検証のための追加拡張子。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有効なプロパティフラグ。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 検証対象のドキュメントページ番号。設定されていない場合、ドキュメントのすべてのページが最初の出現箇所で検証されます（最小値は 1）。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 検証対象のページを指定するページオプションです。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | ヘッダー/フッターの署名を検証するために使用される文書レイアウト内のシェイプ位置です。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
