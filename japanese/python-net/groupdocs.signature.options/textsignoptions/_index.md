---
title: "TextSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "テキスト署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

テキスト署名オプションを表します。

詳細を見る

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

TextSignOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | デフォルト値で TextSignOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | テキストで TextSignOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 署名の背景設定。 |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 枠線設定。 |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 署名のフォント。 |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | 署名の前景色。 |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | テキスト署名を配置するテキストフォームフィールドのタイトル。`signature_implementation` が `TextSignatureImplementation.FORM_FIELD` に設定されている場合にのみ使用できます。 |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | テキスト署名を配置するフォームフィールドのタイプ。このプロパティは `signature_implementation` が `TextSignatureImplementation.FORM_FIELD`（つまり TextToFormField）に設定されている場合にのみ適用されます。デフォルト値は `FormTextFieldType.ALL_TEXT_TYPES` です。 |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | ドキュメントページ上の署名の高さ（ピクセル、パーセント、またはミリメートルの測定値）。単位は `SizeMeasureType` プロパティで決定されます。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | ドキュメントページ上の署名の水平配置です。 |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | ドキュメントページ上の署名の左側 X 位置（`MeasureType` の LocationMeasureType プロパティで定義されたピクセル、パーセント、またはミリメートルの測定値）。水平揃えが指定されていない場合に機能します。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | `left` と `top` プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | 署名とドキュメントの端との間のスペース。水平または垂直揃えが指定されている場合にのみ適用されます。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）です。 |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | ネイティブ属性。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | ドキュメントページ上の署名の回転角度（時計回り）です。 |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | シェイプの位置は、シェイプがドキュメントレイアウト内でどこに表示されるかを定義します。Word ドキュメントでのみ利用可能です。 |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | テキストを配置する形状のタイプ。 |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | 署名の一意の ID。検証オプションで使用でき、PDF ドキュメントでのみサポートされます。 |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | テキスト署名実装のタイプ。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Width および Height プロパティの測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | ドキュメントページ上のストレッチモード。 |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | 署名のテキスト。 |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | 署名内のテキストの水平揃え。Image および Annotation 署名実装でのみサポートされます（`TextSignatureImplementation` の SignatureImplementation プロパティを参照）。 |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | 署名内のテキストの垂直配置。 |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | ドキュメントページ上の署名の上部 Y 位置。測定単位（ピクセル、パーセント、またはミリメートル）で表されます。 |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | 署名の透明度。0.0（不透明）から 1.0（透明）までの浮動小数点数です。デフォルトは 0.0（不透明）です。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | ドキュメントページ上の署名の垂直位置揃え。 |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | ドキュメントページ上の署名の幅（ピクセル、パーセント、またはミリメートルの測定値；`MeasureType` と `SizeMeasureType` プロパティを参照）。 |
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
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
`TextSignOptions` を使用するタスクガイド：

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
