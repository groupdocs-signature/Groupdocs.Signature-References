---
title: "テキスト署名による電子署名ドキュメント"
linkTitle: "Text Signature"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "この記事では、GroupDocs.Signature for Python via .NET API を使用してテキスト署名で文書に署名する方法を説明します。Python でプログラム的に PDF にデジタル署名を追加する方法を学びます。"
type: docs
url: /ja/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

**Text** 電子署名は、文書の種類に応じてネイティブな方法で文書に追加される任意のテキストです。GroupDocs.Signature はテキスト署名機能を提供し、フォント名、サイズ、色から配置、枠線、影効果など、幅広いテキスト設定をカスタマイズできます。テキスト署名は以下のようになります：

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Python を使用してプログラム的に PDF にテキスト署名を追加してみましょう。

テキスト署名をプログラム的に操作するには、[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) が [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) クラスを提供しており、全体のワークフローは以下のように簡単です：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

この例は、Python を使用して文書にテキスト署名を追加する方法を示しています：

{{< tabs \"sign_with_text_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # テキスト署名オプションを作成する
        options = TextSignOptions("John Smith")

        # 署名の位置とサイズを設定する
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # テキストの色とフォントを設定する
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # ドキュメントに署名し、結果を保存する
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

テキスト署名は、配置や余白、フォントスタイル、背景、枠線、回転、透明度といった追加オプションでさらにカスタマイズできます。配置が設定されると、`left` または `top` の座標が置き換えられ、`margin` はページの端から署名のオフセットを指定します。

{{< tabs "sign_with_text_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # ページの右下隅に署名を配置します
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # フォントスタイルとテキストカラー
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # 背景、枠線、回転、透明度
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # テキストを画像としてレンダリングし、PDFページ上に枠線も描画します
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
このガイドでは、[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) を使用してドキュメントにテキストベースの署名を追加する方法を説明します。フォント、カラー、サイズ、位置などのテキストプロパティの設定と、ドキュメントへのテキスト署名の適用について解説しています。署名が追加されたドキュメントは、テキスト署名と共に保存されます。

## More Resources

### GitHub Examples

上記のコードを簡単に実行して、GitHub のサンプルで機能を実際に確認できます:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

フル機能の Python ライブラリに加えて、シンプルで強力な無料オンラインアプリも提供しています。

PDF、Word、Excel、PowerPoint、その他のドキュメントに署名するには、**[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** のオンラインアプリを使用できます。
