---
title: "DigitalSignOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デジタル署名オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

デジタル署名オプションを表します。

詳細を見る

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

DigitalSignOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | DigitalSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | 証明書ファイルを使用して新しい DigitalSignOptions インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | 証明書ストリームを使用して新しい DigitalSignOptions インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | 証明書ファイルと外観画像ファイルを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | 証明書ファイルと外観画像ストリームを使用して DigitalSignOptions の新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | 証明書ストリームと外観画像ファイルを使用して DigitalSignOptions の新しいインスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | 証明書ストリームと外観画像ストリームを使用して新しい DigitalSignOptions インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 内部リソースをクリアします。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Base64 文字列から事前定義された画像を使用して新しい ImageSignOptions インスタンスを作成します。（[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | 有効期限が切れた証明書で署名できるフラグです。デフォルト値は False です。期限切れの証明書で署名しようとすると `GroupDocsSignatureException` がスローされ、ドキュメントは署名されません。 |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | 有効期間がまだ開始されていない証明書で署名できるフラグです。デフォルト値は False です。そのような証明書で署名しようとすると `GroupDocsSignatureException` がスローされ、ドキュメントは署名されません。 |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | デジタル証明書ファイルのパスです。 |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | デジタル証明書ストリームです。このプロパティが指定されている場合、常に CertificateFilePath の代わりに使用されます。 |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | 署名の連絡先です。 |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | ドキュメントに署名するために使用されるカスタムハッシュ署名関数で、ユーザーが独自のデジタル署名ロジックを実装できるようにします。 |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | ドキュメントページ上の署名領域の高さ（測定単位：ピクセル、パーセント、またはミリメートル；`MeasureType` を参照）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | ドキュメントページ上の画像の水平配置です。 |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | ドキュメントページ上の署名領域の左側 X 位置（測定単位：ピクセル、パーセント、または `MeasureType.location_measure_type` で定義されたミリメートル）。 |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | 署名の位置です。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | 左側および上側プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | 画像とドキュメントの端の間にデフォルトで指定される余白（水平または垂直の配置が指定された場合に適用）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | 余白の測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | デジタル証明書のパスワードです。 |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | 署名の理由です。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | 時計回りの回転角です。 |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | ドキュメントのデジタル署名プロパティです。PDF 署名の場合、[`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/) インスタンスを使用して高度なプロパティを設定できます。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Width および Height プロパティの測定単位（ピクセル、パーセント、またはミリメートル）です。 |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | ドキュメントページ上の伸縮モードです。 |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | ドキュメントページ上の署名領域の上側 Y 位置（測定単位：ピクセル、パーセント、またはミリメートル；`MeasureType` `LocationMeasureType` を参照）。 |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | デジタル署名の透明度（0.0 から 1.0 の範囲）。デフォルトは 0 です。 |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | The LTV（Long Term Validation）検証フラグ。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | ドキュメントページ上の画像の垂直配置です。 |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | 署名の可視性。 |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | ドキュメントページ上の署名領域の幅を測定値（ピクセル、パーセント、またはミリメートル）で指定します。測定単位は `MeasureType` によって SizeMeasureType プロパティで定義されます。 |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | XAdES タイプです。デフォルト値は None（XAdES はオフ）です。 |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # コンストラクタに証明書と外観画像を渡します
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # ページ上に署名を、この位置とサイズで表示します
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # 署名に格納された情報
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
`DigitalSignOptions` を使用するタスクガイド：

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
