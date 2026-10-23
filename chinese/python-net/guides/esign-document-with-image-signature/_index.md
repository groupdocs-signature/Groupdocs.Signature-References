---
title: "使用图像签名的电子签文档"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "本文演示了如何使用 GroupDocs.Signature for Python via .NET 在文档页面上添加签名图像。"
type: docs
url: /zh/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

将 **image** 作为签名是一种以可视化形式呈现数据的替代方式。这种电子签名类型允许创建带有公司标志、发送者首字母、姓名等的自定义图像。

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

以下是在文档页面上创建图像签名的步骤：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

本示例展示了如何使用 Python 使用图像签名对 PDF 文档进行签署：

{{< tabs \"sign_with_image_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # 使用图像文件创建图像签名选项
        options = ImageSignOptions("signature.jpg")

        # 设置签名的位置和大小
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # 对文档进行签名并保存结果
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) 下载它。

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

您可以通过额外选项进一步自定义图像签名：对齐和边距、旋转、透明度以及边框。当设置对齐时，它会替代 `left` 或 `top` 坐标，`margin` 则将签名相对于页面边缘进行偏移。

{{< tabs \"sign_with_image_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # 将签名放置在页面的右下角
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 旋转图像并将其透明度设为 20%
        options.rotation_angle = 10
        options.transparency = 0.2

        # 在图像周围绘制虚线边框
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) 下载它。

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

您也可以从流中加载签名图像。保持流打开，直至 `sign` 返回：

{{< tabs \"sign_with_image_from_stream\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # 从流中加载签名图像
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) 下载它。

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) 下载它。

{{< /tab >}}
{{< tab \"signed_image_stream.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
本指南演示如何使用 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) 向文档添加基于图像的签名。它涵盖了文档的加载、图像签名属性的配置（如大小、位置和透明度），以及已签名文档的保存。还讨论了高级自定义选项，例如调整图像外观和对齐签名。欲获取更多见解，请探索相关的文档签署资源。

## More Resources

### GitHub Examples

您可以轻松运行上述代码，并在我们的 GitHub 示例中看到该功能的实际效果：

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

除了功能齐全的 Python 库外，我们还提供简单但强大的免费在线应用程序。

要免费生成图像签名和/或使用它们对文件进行签名，您可以使用在线应用程序 [Generate Image](https://products.groupdocs.app/signature/generate/image)。

要签署 PDF、Word、Excel、PowerPoint 等文档，您可以使用 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** 中的其他在线应用程序。
