---
title: "使用二维码签名进行电子签署文档"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "本文说明了如何使用 GroupDocs.Signature for Python 通过 .NET API，在文档页面上使用二维码电子签名对文档进行签署。"
type: docs
url: /zh/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR code（或 Quick Response code）是一种二维[barcode](/signature/python-net/guides/esign-document-with-barcode-signature/)，由排列在白色背景上方的方形网格中的黑色方块组成。QR 码可以通过智能手机摄像头或专用的 QR 读取设备读取——手持扫描仪、便携终端、桌面扫描仪、嵌入式扫描仪等。通常，QR 码包含指向网站或应用程序、电子邮件、电话号码、产品标识符或追踪器的数据。因此，QR 码的应用范围从一般营销和商品识别扩展到文档管理。

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec 码 | DataMatrix 码 | GS1 DataMatrix | GS1 QR 码 | QR |
| --- | --- | --- | --- | --- | --- |
| **Application** | * 运输和票务;<br> * 航空业用于电子登机牌;<br> * 铁路用于在线售票并由客户打印或在手机屏幕上显示的车票。车票由列车工作人员或闸机处使用手持扫描仪扫描以验证;<br> * 医疗 - 患者身份腕带和一次性药物标签等. | * 印刷媒体，如标签和信件;<br> * 工业工程用途——标记组件等;<br>  * 食品行业——防止食品包装和日期标注错误; | 用于<br> * 医疗保健;<br> * 政府;<br> * 工业.<br> 编码项目的附加信息，例如:<br> * 重量;<br> * 有效期;<br> * 批号;<br> * 生产日期;<br> * 等等. | 在营销中用于在包装上编码额外的商品信息 | 广泛用于汽车行业和移动应用。适用于编码大量数据字符和特定 URL。 |
| **Length** | 3067 个字母数字,<br> 3832 个数字,<br> 1914 字节 | 2335 个字母数字,<br> 3116 个数字 | 2335 个字母数字,<br> 3116 个数字,<br> 1556 字节 | 7089 字母数字,<br> 4296 数字,<br> 2953 字节 | 4296 字母数字,<br> 7089 数字,<br> 2953 字节 |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

在向文档添加 QR 码电子签名时，主要设置是要编码的文本和 [QR 码的类型](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields)，应通过 [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) 类指定。

以下是使用 QR 码签名对文档进行电子签名的步骤：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

下面的代码片段演示了如何使用 Python 对 PDF 文档进行 QR 码签名：

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # 创建包含待编码文本的 QR 码签名选项
        options = QrCodeSignOptions("John Smith")

        # 设置 QR 码类型
        options.encode_type = QrCodeTypes.QR

        # 设置 QR 码的位置和大小
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # 对文档进行签名并保存结果
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) 下载。

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

上表中的其他 QR 码类型以相同方式设置，例如 `QrCodeTypes.AZTEC` 或 `QrCodeTypes.DATA_MATRIX`。

### Advanced QR Code Options

以下示例展示了如何创建更复杂的 QR 码签名，并进行额外自定义：对齐和边距、模块颜色、背景和边框：

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 将文本和 QR 码类型传递给构造函数
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # 将 QR 码放置在页面的右下角
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 模块颜色、背景以及带有内部间距的点状边框
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) 下载。

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
本指南演示了如何使用 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) 向文档添加 QR 码签名。它包括生成 QR 码签名、配置其属性（如大小和编码）以及将其应用于文档的步骤。QR 码签名可用于快速验证已签署的文档。

## More Resources

### GitHub Examples

您可以轻松运行上述代码，并在我们的 GitHub 示例中看到该功能的实际效果：

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

除了功能齐全的 Python 库外，我们还提供简单但强大的免费在线应用程序。

要免费生成 QR 码和/或使用 QR 码签署文件，您可以使用在线应用程序 [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode)。

要签署 PDF、Word、Excel、PowerPoint 等文档，您可以使用 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** 中的其他在线应用程序。
