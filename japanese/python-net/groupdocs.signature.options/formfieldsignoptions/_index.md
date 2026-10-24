---
title: "FormFieldSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PDF ドキュメントの FormField 署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

PDF ドキュメントの FormField 署名オプションを表します。

PDF ファイル内のフォームフィールド署名を作成または更新するためのオプションを提供します。

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

FormFieldSignOptions 型は以下のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | PdfFormFieldSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | PdfFormFieldSignOptions クラスの新しいインスタンスを FormField 署名で初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | ドキュメントページ上の署名領域の高さ（測定単位はピクセル、パーセント、またはミリメートル；`MeasureType` SizeMeasureType を参照）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | ドキュメントページ上の画像の水平配置です。 |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | ドキュメントページ上の署名領域の左側 X 位置（測定単位はピクセル、パーセント、またはミリメートル）。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Left および Top プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | 画像とドキュメントの端とのデフォルト間隔（水平または垂直の配置が設定されている場合に適用）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | 時計回りに測定された回転角度です。 |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | 署名の FormField。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Width および Height プロパティの測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | ドキュメントページ上のストレッチモード。 |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | ドキュメントページ上の署名領域の上部 Y 位置を測定単位（ピクセル、パーセント、またはミリメートル）で示します。場所の測定タイプについては `MeasureType` を参照してください。 |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | フォームフィールド署名の透明度。値は 0.0 から 1.0 の範囲で、デフォルトは 0 です。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | ドキュメントページ上の画像の垂直配置です。 |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | ドキュメントページ上の署名領域の幅（測定単位はピクセル、パーセント、またはミリメートル；`MeasureType` SizeMeasureType を参照）。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 署名はすべてのドキュメントページに配置されます。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 追加の署名外観。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 署名の背景設定。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 枠線設定。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 署名オプションのドキュメントタイプ（`DocumentType`）。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 署名拡張子。（[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) から継承） |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 署名のフォント。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)から継承） |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | 署名の前景色。（[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) から継承） |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
