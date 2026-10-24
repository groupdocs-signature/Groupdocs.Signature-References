---
title: "QrCodeSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "QR コード署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

QR コード署名オプションを表します。

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

QrCodeSignOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | QrCodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | 指定されたテキストで QR コード署名オプションのインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | テキストを使用して QrCodeSignOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | 生成された QR コード画像内のテキストの配置、デフォルト値は None です。 |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | QR コードコンテンツにシリアライズするカスタムオブジェクトです。 |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | QR コード署名テキストまたはデータをエンコードおよびデコードするために使用されるデータ暗号化実装です。 |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | QR コードのタイプです。 |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | QR コードのバーの前景色です。このプロパティを使用すると検証に問題が生じる可能性があるため、注意して使用してください。 |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | ドキュメントページ上の署名領域の高さ（測定単位はピクセル、パーセント、またはミリメートル；`MeasureType` SizeMeasureType を参照）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | ドキュメントページ上の QR コードの水平配置です。 |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | QR コード要素と結果画像の境界間のスペースです。 |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | ドキュメントページ上の署名領域の左側 X 位置（測定単位はピクセル、パーセント、またはミリメートル）です。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | 左と上のプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）です。 |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | QR コードロゴ画像のファイル名です。 |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | QR コードロゴ画像のストリームです。 |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | 画像とドキュメントのエッジ間のデフォルトで指定されるスペースです（水平または垂直の配置が指定されている場合に機能します）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | 余白の測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | ドキュメントページに配置された署名の QR コード画像コンテンツを取得するフラグです。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | `return_content` プロパティが有効な場合に返される QR‑Code 署名の画像コンテンツのファイルタイプです。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | 時計回りの度数で表した回転角度です。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Width および Height プロパティの測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | ドキュメントページ上の伸縮モードです。 |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | ドキュメントページ上の署名領域の上部 Y 位置（測定単位はピクセル、パーセント、またはミリメートル）。単位は `MeasureType` 型の `LocationMeasureType` プロパティで定義されます。 |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | QR コード署名の透明度です。値は 0.0 から 1.0 の範囲で、デフォルトは 0 です。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | ドキュメントページ上の画像の垂直配置です。 |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | ドキュメントページ上の署名領域の幅（測定値は `MeasureType` で定義されたピクセル、パーセント、またはミリメートル）です。 |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # テキストと QR コードのタイプをコンストラクタに渡します
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # ページの右下隅に QR コードを配置します
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # モジュールの色、背景、および内部に余白のある点線の枠
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
`QrCodeSignOptions` を使用するタスク ガイド:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
