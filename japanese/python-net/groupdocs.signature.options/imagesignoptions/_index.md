---
title: "ImageSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "画像署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

画像署名オプションを表します。

詳しくは以下をご覧ください:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

ImageSignOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | デフォルト値で ImageSignOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | 画像ファイルで ImageSignOptions を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | 画像ストリームで新しい ImageSignOptions インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 内部リソースをクリアします。 |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Base64 文字列から事前定義された画像を使用して新しい ImageSignOptions インスタンスを作成します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | 画像署名の枠線設定です。 |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | ドキュメントページ上の署名の高さを測定単位（ピクセル、パーセント、またはミリメートル）で指定します（`MeasureType` SizeMeasureType を参照）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | ドキュメントページ上の署名の水平配置です。 |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | 署名画像のファイルパスです。`image_stream` が指定されていない場合にのみ使用されます。 |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | 署名画像ストリームです。指定された場合、常に ImageFilePath の代わりに使用されます。 |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | ドキュメントページ上の署名の左側 X 位置を測定単位（ピクセル、パーセント、またはミリメートル）で指定します。水平配置が指定されていない場合に機能します。位置測定タイプは `MeasureType` を参照してください。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | 左と上のプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）です。 |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | 署名とドキュメントの端との間の余白です。水平または垂直配置が指定されている場合にのみ機能します。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）です。 |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | 画像をドキュメントに配置する領域の矩形です。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | ドキュメントページ上の署名の回転角度（時計回り）です。 |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | シェイプの位置は、シェイプがドキュメントレイアウト内でどこに表示されるかを定義します。Word ドキュメントでのみ利用可能です。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Width および Height プロパティの測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | ドキュメントページ上の伸縮モードです。 |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | ドキュメントページ上の署名の上側 Y 位置を測定単位（ピクセル、パーセント、またはミリメートル）で指定します（`MeasureType` LocationMeasureType により定義）。垂直配置が指定されていない場合に機能します。 |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | 署名の透明度は 0.0（不透明）から 1.0（透明）までの範囲で、デフォルトは 0（不透明）です。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | ドキュメントページ上の署名の垂直位置揃え。 |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | ドキュメントページ上の署名の幅（測定単位はピクセル、パーセント、またはミリメートルの `MeasureType` サイズ測定タイプ）。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 署名はすべてのドキュメントページに配置されます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 追加の署名外観。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 署名オプションのドキュメントタイプ（`DocumentType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 署名拡張子。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 暗号操作に使用されるハッシュアルゴリズム。PDF ファイルのデジタル署名でのみサポートされます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 署名対象のドキュメントページ番号。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 署名対象ページを指定するオプション。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 署名タイプ（`SignatureType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | テキスト署名の Z 順序位置。重なり合う署名の表示順序を決定します。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # 画像ファイルで画像署名オプションを作成する
        options = ImageSignOptions("signature.jpg")
        # 署名の位置とサイズを設定する
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
`ImageSignOptions` を使用するタスクガイド：

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
