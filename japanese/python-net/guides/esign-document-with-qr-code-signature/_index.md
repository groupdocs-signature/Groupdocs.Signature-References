---
title: "QR コード署名で文書に電子署名"
linkTitle: "QR Code Signature"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "この記事では、.NET API を介した Python 用 GroupDocs.Signature を使用して、文書ページに QR コードとして電子署名を付与する方法を説明します。"
type: docs
url: /ja/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR コード（または Quick Response コード）は、白い背景に黒い正方形が格子状に配置された二次元 [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) の一種です。QR コードはスマートフォンのカメラや、QR 読み取り専用のハンドヘルドスキャナー、ハンディ端末、デスクトップスキャナー、組み込みスキャナーなどの専用デバイスで読み取れます。通常、QR コードはウェブサイトやアプリケーション、メール、電話番号、製品識別子、トラッカーなどを指すデータを含みます。そのため、QR コードの用途は一般的なマーケティングや商品識別から文書管理まで幅広く及びます。

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec コード | DataMatrix コード | GS1 DataMatrix | GS1 QR コード | QR |
| --- | --- | --- | --- | --- | --- |
| **Application** | * 輸送およびチケット販売;<br> * 航空業界での電子搭乗券;<br> * 鉄道で、オンラインで販売され顧客が印刷またはモバイル画面に表示するチケット。コードは列車内スタッフや改札口のハンドヘルドスキャナーで読み取られ、チケットの検証に使用されます。<br> * 医療 - 患者識別用リストバンドや単回使用薬剤のラベルなど。 | * ラベルや文書などの印刷媒体;<br> * 産業工学目的 - 部品のマーキングなど;<br>  * 食品業界 - 食品の誤った包装や日付付けを防止するため; | 使用分野<br> * 医療;<br> * 政府;<br> * 工業.<br> アイテムの追加情報をエンコードします、例として:<br> * 重量;<br> * 有効期限;<br> * バッチ番号;<br> * 製造日;<br> * その他. | マーケティングで、パッケージ上の追加アイテム情報をエンコードするために使用されます | 自動車産業やモバイルアプリで広く使用されています。大量のデータ文字や特定の URL をエンコードするのに便利です。 |
| **Length** | 3067 英数字,<br> 3832 数字,<br> 1914 バイト | 2335 英数字,<br> 3116 数字 | 2335 英数字,<br> 3116 数字,<br> 1556 バイト | 7089 英数字,<br> 4296 数字,<br> 2953 バイト | 4296 英数字,<br> 7089 数字,<br> 2953 バイト |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

ドキュメントに QR コードの電子署名を追加する際、主な設定はエンコードするテキストと、[QR コードのタイプ](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) です。これらは [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) クラスを介して指定します。

QR コード署名でドキュメントに電子署名する手順は以下の通りです：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

以下のコードスニペットは、Python を使用して QR コード署名で PDF ドキュメントに署名する方法を示しています：

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # エンコードするテキストを使用して QR コード署名オプションを作成します
        options = QrCodeSignOptions("John Smith")

        # QR コードのタイプを設定します
        options.encode_type = QrCodeTypes.QR

        # QR コードの位置とサイズを設定します
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # ドキュメントに署名し、結果を保存する
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されているサンプルファイルです。[ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

上の表にある他の QR コードタイプも同様に設定できます。例として `QrCodeTypes.AZTEC` や `QrCodeTypes.DATA_MATRIX` があります。

### Advanced QR Code Options

以下は、配置や余白、モジュールの色、背景、枠線などの追加カスタマイズを伴う、より複雑な QR コード署名を作成する例です：

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
{{< tab "Python" >}}
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
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されているサンプルファイルです。[ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
このガイドでは、[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) を使用してドキュメントに QR コード署名を追加する方法を示します。QR コード署名の生成、サイズやエンコードなどのプロパティ設定、ドキュメントへの適用手順が含まれています。QR コード署名は、署名されたドキュメントの迅速な検証に利用できます。

## More Resources

### GitHub Examples

上記のコードを簡単に実行して、GitHub のサンプルで機能を実際に確認できます:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

フル機能の Python ライブラリに加えて、シンプルで強力な無料オンラインアプリも提供しています。

QR コードを無料で生成したり、QR コードでファイルに署名したりするには、[QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode) オンラインアプリを使用できます。

PDF、Word、Excel、PowerPoint などのドキュメントに署名するには、**[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** の他のオンラインアプリをご利用いただけます。
