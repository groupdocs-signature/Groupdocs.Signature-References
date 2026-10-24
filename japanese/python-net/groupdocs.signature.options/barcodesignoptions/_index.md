---
title: "BarcodeSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "バーコード署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

バーコード署名オプションを表します。

詳細を見る

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

BarcodeSignOptions 型は以下のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | BarcodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | BarcodeSignOptions クラスの新しいインスタンスをテキストで初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | BarcodeSignOptions クラスの新しいインスタンスをテキストで初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | 生成されたバーコード画像内のテキストの配置です。デフォルト値は None です。 |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | バーコードのタイプです。 |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | バーコードのバーの前景色です。使用すると検証に問題が生じる可能性があるため、注意して使用してください。 |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | 文書ページ上の署名領域の高さ（測定単位はピクセル、パーセント、またはミリメートル）。サイズ測定タイプについては `MeasureType` を参照してください。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | ドキュメントページ上の画像の水平配置です。 |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | バーコード要素と結果画像の境界間のスペースです。 |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | 文書ページ上の署名領域の左側 X 位置で、測定単位（ピクセル、パーセント、またはミリメートル）で表されます。`MeasureType` を参照してください。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | 左と上のプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）です。 |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | 水平または垂直配置が設定されている場合に適用される、画像とドキュメントの端の間にデフォルトで指定されるスペースです。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | 余白の測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | 文書ページに配置された署名のバーコード画像コンテンツを取得するかどうかを示すフラグです。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | `return_content` プロパティが有効な場合のバーコード署名の返却画像コンテンツのファイルタイプです。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | 時計回りの回転角です。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Width および Height プロパティの測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | ドキュメントページ上の伸縮モードです。 |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | 文書ページ上の署名領域の上部 Y 位置で、測定単位（ピクセル、パーセント、またはミリメートル）で表されます。`MeasureType` の LocationMeasureType を参照してください。 |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | バーコード署名の透明度で、0.0（完全に不透明）から 1.0（完全に透明）までの範囲です。デフォルトは 0 です。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | ドキュメントページ上のバーコード画像の垂直位置合わせ。 |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | `MeasureType`で定義される測定単位（ピクセル、パーセント、またはミリメートル）で、ドキュメントページ上の署名領域の幅。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 署名はすべてのドキュメントページに配置されます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 追加の署名外観。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 署名の背景設定。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 枠線設定。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 署名オプションのドキュメントタイプ（`DocumentType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 署名拡張子。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 署名のフォント。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | テキスト署名を配置するテキストフォームフィールドのタイトル。`signature_implementation`が`TextSignatureImplementation.FORM_FIELD`に設定されている場合にのみ使用可能です。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | テキスト署名を配置するフォームフィールドのタイプ。このプロパティは`signature_implementation`が`TextSignatureImplementation.FORM_FIELD`（すなわちTextToFormField）に設定されている場合にのみ適用されます。デフォルト値は`FormTextFieldType.ALL_TEXT_TYPES`です。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 暗号操作に使用されるハッシュアルゴリズム。PDF ファイルのデジタル署名でのみサポートされます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | ネイティブ属性。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 署名対象のドキュメントページ番号。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 署名対象ページを指定するオプション。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | シェイプの位置は、ドキュメントレイアウト内でシェイプが表示される場所を定義します。Word文書でのみ利用可能です。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | テキストを配置するシェイプのタイプ。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | 署名の一意なID。検証オプションで使用でき、PDF文書でのみサポートされます。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | テキスト署名実装のタイプ。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 署名タイプ（`SignatureType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | 署名のテキスト。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | 署名内のテキストの水平位置合わせ。ImageおよびAnnotation署名実装でのみサポートされます（`TextSignatureImplementation`のSignatureImplementationプロパティを参照）。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | 署名内のテキストの垂直位置合わせ。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | テキスト署名の Z 順序位置。重なり合う署名の表示順序を決定します。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
`BarcodeSignOptions`を使用するタスクガイド：

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
