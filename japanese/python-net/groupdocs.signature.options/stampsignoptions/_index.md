---
title: "StampSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "スタンプ署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

スタンプ署名オプションを表します。

詳しくは以下をご覧ください:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

StampSignOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | デフォルト値で StampSignOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | 配置オプションで StampSignOptions クラスの新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 内部リソースをクリアします。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Base64 文字列から事前定義された画像を使用して新しい ImageSignOptions インスタンスを作成します。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | スタンプの背景です。 |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | 署名の背景色のクロップタイプです。 |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | 署名の背景画像のクロップタイプです。 |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | ドキュメントページ上の署名領域の高さ（測定単位はピクセル、パーセント、またはミリメートル）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | ドキュメントページ上の画像の水平配置です。 |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | 内部線のリストは矩形の集合として描画されます。 |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | ドキュメントページ上の署名領域の左側X位置（測定単位はピクセル、パーセント、またはミリメートル）。`MeasureType` `LocationMeasureType` を参照してください。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | 左側および上側プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | 画像とドキュメントの端の間にデフォルトで指定されるスペース（水平または垂直の配置が指定されている場合に機能します）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | 余白の測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | 外側の線のリストは同心円として描画されます。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | 時計回りの回転角です。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Width および Height プロパティの測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | スタンプのタイプです。デフォルトは `Round` です。 |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | ドキュメントページ上の伸縮モードです。 |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | ドキュメントページ上の署名領域の上側Y位置（測定単位はピクセル、パーセント、またはミリメートル）。`MeasureType` `LocationMeasureType` を参照してください。 |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | スタンプ署名の透明度です。値は0.0から1.0の範囲で、デフォルトは0です。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | ドキュメントページ上のスタンプの垂直配置です。 |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | ドキュメントページ上の署名領域の幅（測定値はピクセル、パーセント、またはミリメートル）。測定単位は `MeasureType` の SizeMeasureType で定義されます。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 署名はすべてのドキュメントページに配置されます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 追加の署名外観。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | 画像署名の境界設定です。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 署名オプションのドキュメントタイプ（`DocumentType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 署名拡張子。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 暗号操作に使用されるハッシュアルゴリズム。PDF ファイルのデジタル署名でのみサポートされます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | 署名画像のファイルパスです。`image_stream` が指定されていない場合にのみ使用されます。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | 署名画像ストリームです。指定された場合、常に ImageFilePath の代わりに使用されます。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 署名対象のドキュメントページ番号。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 署名対象ページを指定するオプション。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | 画像を文書に配置する領域の矩形です。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | 形状の位置は、文書レイアウト内で形状が表示される場所を定義します。Word 文書でのみ利用可能です。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 署名タイプ（`SignatureType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | テキスト署名の Z 順序位置。重なり合う署名の表示順序を決定します。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # 必要に応じて追加のスタンプオプションを構成します
    signature.sign(options)
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
