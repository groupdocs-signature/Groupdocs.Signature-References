---
title: "使用条形码签名进行电子签署文档"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "本文说明了如何使用 GroupDocs.Signature for Python via .NET 在文档页面上添加条形码签名，并提供条形码类型、条形码文本、定位、对齐以及其他视觉设置等多种选项。"
type: docs
url: /zh/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

**条形码** 或 **条码** 是以可视化、机器可读的形式呈现数据的一种方式。一般来说，条形码是一种矩形图像，由不同宽度的平行黑线和白色空格组成。
条形码被广泛用于需要快速识别的各个领域——在零售店的购买流程中、在仓库中用于跟踪库存、以及在发票上辅助会计等众多用途。

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

条形码可以存储与产品相关的数据，如生产日期和有效期、制造商名称、原产国以及产品价格。如今条形码类型繁多，因为不同公司根据需求在条形码中使用不同的数字和条纹组合。从文档签名的角度来看，条形码可以包含不同的字符（字母、数字或符号），并且根据类型和设置，其长度和尺寸可能各不相同，以保存签名信息、标题、主题或简短的加密数据。

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
要为条形码签名指定不同的选项，GroupDocs.Signature for Python via .NET 提供了 [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) 类。主要字段包括：

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

以下是使用 GroupDocs.Signature for Python via .NET API 通过条形码签名对文档进行电子签名的步骤：
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

此示例展示了如何使用 Python 对 PDF 文档进行条形码签名：

{{< tabs "sign_with_barcode_signature" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # 创建包含待编码文本的条形码签名选项
        options = BarcodeSignOptions("John Smith")

        # 设置条形码类型
        options.encode_type = BarcodeTypes.CODE128

        # 设置条形码的位置和大小
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # 对文档进行签名并保存结果
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) 下载。

{{< /tab >}}
{{< tab \"signed_barcode.pdf\" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

您可以通过以下附加选项进一步自定义条形码签名：对齐和边距、条形颜色、编码文本的位置、内部边距、背景、边框和透明度：

{{< tabs \"sign_with_barcode_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 将文本和条形码类型传递给构造函数
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # 将条形码放置在页面的右下角
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 条形颜色、条形下方的编码文本、边框内部的间距
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # 背景、边框和透明度
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) 下载。

{{< /tab >}}
{{< tab \"signed_barcode_advanced.pdf\" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature 支持多种条形码类型。每种类型接受各自的字符集和长度，因此请选择与类型匹配的文本。此示例在一次调用中为文档签署四个不同类型的条形码：

{{< tabs \"sign_with_different_barcode_types\" >}}
{{< tab \"Python\" >}}
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

    # 每个条形码对应一个签名选项对象，依次排列
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) 下载。

{{< /tab >}}
{{< tab \"signed_barcode_types.pdf\" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
本指南演示如何使用 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) 将基于条形码的签名添加到文档中。它涵盖了创建、配置和应用条形码签名，并支持多种条形码类型和自定义选项。欲进一步了解，请参阅有关文档信息和高级签名技术的相关指南。

## More Resources

### GitHub Examples

您可以轻松运行上述代码，并在我们的 GitHub 示例中看到该功能的实际效果：

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

除了功能齐全的 Python 库外，我们还提供简单但强大的免费在线应用程序。

要免费生成条形码和/或使用条形码签署文件，您可以使用在线应用程序 [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode)。

要签署 PDF、Word、Excel、PowerPoint 等文档，您可以使用 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** 中的其他在线应用程序。
