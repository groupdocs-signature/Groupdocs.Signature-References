---
title: "使用多签名的电子签名文档"
linkTitle: "Multiple Types eSign"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "本文说明了如何通过 GroupDocs.Signature for Python via .NET API 对文档进行多种类型的多重签名"
type: docs
url: /zh/python-net/guides/esign-document-with-multiple-signatures/
is_root: false
weight: 80
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) allows signing a document with several signatures simultaneously and even apply signatures of different types to the same document.

实现此操作非常简单：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path or stream as a constructor parameter.
* Instantiate all required sign options objects depending on signature type:
    * [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) - for Barcode signatures;
    * [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) - for Digital signatures;
    * [FormFieldSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/formfieldsignoptions) - for Form-field signatures;
    * [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) - for Image signatures;
    * [MetadataSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/metadatasignoptions) - for Metadata signatures;
    * [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) - for QR-code signatures
    * [StampSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/stampsignoptions) - for Stamp signatures;
    * [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) - for Text signatures.
* Fill the collection with sign options from the previous step.  
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the collection of sign options to it.

下面的代码片段演示了如何使用 Python 同时对 PDF 文档进行多重电子签名：

{{< tabs \"sign_with_multiple_signatures\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import (
    BarcodeSignOptions, DigitalSignOptions, QrCodeSignOptions, TextSignOptions)
from groupdocs.signature.domain import BarcodeTypes, QrCodeTypes

def sign_with_multiple_signatures():
    with Signature("sample.pdf") as signature:
        # 定义文本签名选项
        text_options = TextSignOptions("This is test message")
        text_options.left = 100
        text_options.top = 360
        text_options.width = 200
        text_options.height = 30

        # 定义条形码签名选项
        barcode_options = BarcodeSignOptions("123456")
        barcode_options.encode_type = BarcodeTypes.CODE128
        barcode_options.left = 100
        barcode_options.top = 420
        barcode_options.width = 200
        barcode_options.height = 60

        # 定义二维码签名选项
        qrcode_options = QrCodeSignOptions("JohnSmith")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.left = 100
        qrcode_options.top = 520
        qrcode_options.width = 100
        qrcode_options.height = 100

        # 定义带有证书和外观图像的数字签名选项
        digital_options = DigitalSignOptions("certificate.pfx")
        digital_options.password = "1234567890"
        digital_options.image_file_path = "signature.jpg"
        digital_options.left = 350
        digital_options.top = 520
        digital_options.width = 160
        digital_options.height = 100

        # 使用签名选项列表对文档进行签名
        list_options = [text_options, barcode_options, qrcode_options, digital_options]
        result = signature.sign("signed_multiple.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击[此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf)下载。

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` 是本示例中使用的示例证书（密码 `1234567890`）。点击[此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/certificate.pfx)下载。

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` 是本示例中使用的示例文件。点击[此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/signature.jpg)下载。

{{< /tab >}}
{{< tab "signed_multiple.pdf" >}}
```text
Binary file (PDF, 740 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures/signed_multiple.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Multiple Signatures Example

以下是一个更高级的示例，展示如何添加具有不同样式和位置的多个签名。每个签名都通过对齐方式并相对于页面边缘设置边距进行放置：

{{< tabs "sign_with_multiple_signatures_advanced" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions, QrCodeSignOptions, TextSignOptions
from groupdocs.signature.domain import (
    HorizontalAlignment, Padding, QrCodeTypes, SignatureFont, VerticalAlignment)

def sign_with_multiple_signatures_advanced():
    with Signature("sample.pdf") as signature:
        # 页面标题下方右上角的粗体文本签名
        text_options = TextSignOptions("Approved by John Smith")
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        text_options.font = font
        text_options.width = 280
        text_options.height = 40
        text_options.vertical_alignment = VerticalAlignment.TOP
        text_options.horizontal_alignment = HorizontalAlignment.RIGHT
        text_options.margin = Padding(top=170, right=20)

        # 左下角的印章图像
        image_options = ImageSignOptions("stamp.png")
        image_options.width = 100
        image_options.height = 100
        image_options.vertical_alignment = VerticalAlignment.BOTTOM
        image_options.horizontal_alignment = HorizontalAlignment.LEFT
        image_options.margin = Padding(left=20, bottom=20)

        # 右下角的二维码
        qrcode_options = QrCodeSignOptions("https://www.example.com/verify")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.width = 100
        qrcode_options.height = 100
        qrcode_options.vertical_alignment = VerticalAlignment.BOTTOM
        qrcode_options.horizontal_alignment = HorizontalAlignment.RIGHT
        qrcode_options.margin = Padding(right=20, bottom=20)

        # 使用签名选项列表对文档进行签名
        list_options = [text_options, image_options, qrcode_options]
        result = signature.sign("signed_multiple_advanced.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures_advanced()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击[此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf)下载。

{{< /tab >}}
{{< tab "stamp.png" >}}

`stamp.png` 是本示例中使用的示例文件。点击[此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/stamp.png)下载。

{{< /tab >}}
{{< tab "signed_multiple_advanced.pdf" >}}
```text
Binary file (PDF, 178 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures_advanced/signed_multiple_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
本指南演示如何使用 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) 将多种电子签名（例如文本、条形码、图像）应用于文档。它说明了如何组合不同的签名类型、配置每种签名，并以多种签名样式保存已签名的文档。

## More Resources

### GitHub Examples

您可以轻松运行上述代码，并在我们的 GitHub 示例中看到该功能的实际效果：

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

除了功能齐全的 Python 库外，我们还提供简单但强大的免费在线应用程序。

要对 PDF、Word、Excel、PowerPoint 以及其他文档进行签名，您可以使用 **[GroupDocs.Signature 应用产品系列](https://products.groupdocs.app/signature/family)** 中的在线应用。
