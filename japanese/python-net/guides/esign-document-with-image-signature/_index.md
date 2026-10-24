---
title: "画像署名による eSign ドキュメント"
linkTitle: "Image Signature"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "この記事では、.NET 経由で Python 用 GroupDocs.Signature を使用して文書ページに署名画像を追加する方法を示します。"
type: docs
url: /ja/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

署名としての **image** は、提示データを視覚的に表現する代替手段です。この電子署名タイプでは、会社ロゴ、送信者のイニシャル、名前などを使用したカスタム画像の作成が可能です。

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

文書ページに画像署名を作成する手順は次のとおりです：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

この例は、Python を使用して画像署名で PDF 文書に署名する方法を示しています：

{{< tabs "sign_with_image_signature" >}}
{{< tab "Python" >}}
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

        # ドキュメントに署名し、結果を保存する
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) をクリックしてください。

{{< /tab >}}
{{< tab "signed_image.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

画像署名は、配置や余白、回転、透明度、枠線といった追加オプションでさらにカスタマイズできます。配置を設定すると、`left` または `top` の座標が置き換えられ、`margin` はページ端から署名のオフセットを指定します。

{{< tabs "sign_with_image_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # ページの右下隅に署名を配置します
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 画像を回転させ、20% の透明度にします
        options.rotation_angle = 10
        options.transparency = 0.2

        # 画像の周囲に破線の枠線を描画します
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) をクリックしてください。

{{< /tab >}}
{{< tab "signed_image_advanced.pdf" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

ストリームから署名画像を読み込むこともできます。`sign` が返るまでストリームを開いたままにしてください:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # ストリームから署名画像を読み込む
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) をクリックしてください。

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
このガイドでは、[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) を使用してドキュメントに画像ベースの署名を追加する方法を示します。ドキュメントの読み込み、画像署名のプロパティ（サイズ、位置、透明度など）の設定、署名済みドキュメントの保存について説明します。また、画像の外観調整や署名の配置など、詳細なカスタマイズオプションも取り上げています。さらに詳しい情報については、関連するドキュメント署名リソースをご参照ください。

## More Resources

### GitHub Examples

上記のコードを簡単に実行して、GitHub のサンプルで機能を実際に確認できます:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

フル機能の Python ライブラリに加えて、シンプルで強力な無料オンラインアプリも提供しています。

画像署名を作成したり、無料でファイルに署名したりするには、[Generate Image](https://products.groupdocs.app/signature/generate/image) オンラインアプリを使用できます。

PDF、Word、Excel、PowerPoint などのドキュメントに署名するには、**[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** の他のオンラインアプリをご利用いただけます。
