---
title: "使用文本签名的电子签名文档"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "本文说明如何使用 GroupDocs.Signature for Python via .NET API 通过文本签名对文档进行签名。了解如何在 Python 中以编程方式向 PDF 添加数字签名。"
type: docs
url: /zh/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

**Text** 电子签名是一段任意文本，根据文档类型以原生方式添加到文档中。GroupDocs.Signature 提供文本签名功能，并允许自定义广泛的文本设置——从字体名称、大小、颜色到对齐方式、边框、阴影效果等。文本签名可能如下所示：

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

让我们尝试使用 Python 以编程方式向 PDF 添加文本签名。

要以编程方式操作文本签名，[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) 提供了 [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) 类，整个工作流程如下所示：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

本示例展示了如何使用 Python 向文档添加文本签名：

{{< tabs "sign_with_text_signature" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # 创建文本签名选项
        options = TextSignOptions("John Smith")

        # 设置签名的位置和大小
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # 设置文本颜色和字体
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # 对文档进行签名并保存结果
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"signed_text.pdf\" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

您可以通过额外选项进一步自定义文本签名：对齐方式和边距、字体样式、背景、边框、旋转和透明度。设置对齐方式后，它会替代 `left` 或 `top` 坐标，`margin` 则将签名相对于页面边缘进行偏移。

{{< tabs \"sign_with_text_signature_advanced\" >}}
{{< tab \"Python\" >}}
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

        # 将签名放置在页面的右下角
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 字体样式和文本颜色
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # 背景、边框、旋转和透明度
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

        # 将文本渲染为图像，同时在 PDF 页面上绘制边框
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"signed_text_advanced.pdf\" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
本指南说明如何使用 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) 向文档添加基于文本的签名。它涵盖了字体、颜色、大小和位置等文本属性的配置，以及将文本签名应用于文档。随后，已签名的文档将保存为包含添加的文本签名的文件。

## More Resources

### GitHub Examples

您可以轻松运行上述代码，并在我们的 GitHub 示例中看到该功能的实际效果：

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

除了功能齐全的 Python 库外，我们还提供简单但强大的免费在线应用程序。

要对 PDF、Word、Excel、PowerPoint 以及其他文档进行签名，您可以使用 **[GroupDocs.Signature 应用产品系列](https://products.groupdocs.app/signature/family)** 中的在线应用。
