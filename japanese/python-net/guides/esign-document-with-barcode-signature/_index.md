---
title: "バーコード署名でドキュメントに電子署名"
linkTitle: "Barcode Signature"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "この記事では、GroupDocs.Signature for Python via .NET を使用して、バーコードタイプ、バーコードテキスト、位置指定、配置、その他のビジュアル設定など、さまざまなオプションでドキュメントページにバーコード署名を追加する方法を説明します。"
type: docs
url: /ja/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

**barcode** または **bar code** は、データを視覚的で機械可読な形で表現する方法です。一般的に、バーコードは異なる幅の平行な黒線と白いスペースからなる長方形の画像です。
バーコードは、迅速な識別が必要なさまざまな分野で使用されます。小売店での購入プロセスの一部、倉庫での在庫管理、請求書での会計支援など、多くの用途があります。

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

バーコードは、製造日や有効期限、メーカー名、原産国、製品価格など、製品に関するデータを保存することができます。現在では、企業ごとにニーズに合わせて異なる数字やバーの組み合わせを使用するため、さまざまなバーコードタイプが存在します。ドキュメント署名の観点からは、Barcode は文字（英字、数字、記号）を含むことができ、タイプや設定に応じて長さやサイズが異なり、署名情報、タイトル、件名、または短い暗号化データを保持することができます。

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Barcode 署名のさまざまなオプションを指定するには、GroupDocs.Signature for Python via .NET が提供する [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) クラスを使用します。主なフィールドは次のとおりです:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

GroupDocs.Signature for Python via .NET API を使用して、Barcode 署名でドキュメントに電子署名する手順は以下の通りです:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

この例は、Python を使用して PDF ドキュメントに Barcode 署名を付与する方法を示しています:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # エンコードするテキストでバーコード署名オプションを作成します
        options = BarcodeSignOptions("John Smith")

        # バーコードのタイプを設定します
        options.encode_type = BarcodeTypes.CODE128

        # バーコードの位置とサイズを設定します
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # ドキュメントに署名し、結果を保存する
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

バーコード署名をさらにカスタマイズするには、追加オプションを使用できます：配置と余白、バーの色、エンコードされたテキストの位置、内部余白、背景、枠線、透明度：

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # テキストとバーコードタイプをコンストラクタに渡します
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # ページの右下隅にバーコードを配置します
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # バーの色、バーの下にエンコードされたテキスト、枠線内の余白
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # 背景、枠線、透明度
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature はさまざまなバーコードタイプをサポートしています。各タイプはそれぞれの文字セットと長さを受け入れるため、タイプに合わせたテキストを選択してください。この例では、1 回の呼び出しで異なるタイプのバーコードを 4 つ文書に署名します：

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # バーコードごとに 1 つのサインオプションオブジェクトを使用し、上下に配置します
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
このガイドでは、[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) を使用してドキュメントにバーコードベースの署名を追加する方法を示します。さまざまなバーコードタイプとカスタマイズオプションをサポートしたバーコード署名の作成、構成、適用について説明しています。さらに詳しくは、ドキュメント情報や高度な署名手法に関する関連ガイドをご参照ください。

## More Resources

### GitHub Examples

上記のコードを簡単に実行して、GitHub のサンプルで機能を実際に確認できます:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

フル機能の Python ライブラリに加えて、シンプルで強力な無料オンラインアプリも提供しています。

バーコードを生成したり、無料でファイルにバーコード署名を付与したりするには、[Barcode Generator](https://products.groupdocs.app/signature/generate/barcode) オンラインアプリをご利用ください。

PDF、Word、Excel、PowerPoint などのドキュメントに署名するには、**[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** の他のオンラインアプリをご利用いただけます。
