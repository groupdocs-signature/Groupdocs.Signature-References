---
title: "DigitalSignOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示数字签名选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

表示数字签名选项。

了解更多

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

DigitalSignOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | 使用默认值初始化 DigitalSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | 使用证书文件初始化新的 DigitalSignOptions 实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | 使用证书流初始化新的 DigitalSignOptions 实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | 使用证书文件和外观图像文件初始化 DigitalSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | 使用证书文件和外观图像流初始化 DigitalSignOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | 使用证书流和外观图像文件初始化 DigitalSignOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | 使用证书流和外观图像流初始化新的 DigitalSignOptions 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 清除内部资源。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | 使用 Base64 字符串中的预定义图像创建新的 ImageSignOptions 实例。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | 允许使用已过期证书进行签名的标志。默认值为 False；使用已过期的证书签名会抛出 `GroupDocsSignatureException`，并且文档不会被签名。 |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | 允许使用尚未生效的证书进行签名的标志。默认值为 False；使用此类证书签名会抛出 `GroupDocsSignatureException`，并且文档不会被签名。 |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | 数字证书文件路径。 |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | 数字证书流。如果指定此属性，则始终使用它而不是 CertificateFilePath。 |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | 签名联系人。 |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | 用于签署文档的自定义哈希签名函数，允许用户实现自己的数字签名逻辑。 |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | 文档页面上签名区域的高度，使用测量单位（像素、百分比或毫米；参见 `MeasureType`）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | 图像在文档页上的水平对齐方式。 |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | 文档页面上签名区域的左侧 X 位置，使用测量单位（像素、百分比或由 `MeasureType.location_measure_type` 定义的毫米）。 |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | 签名位置。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | 默认情况下图像与文档边缘之间的间距（在指定水平或垂直对齐时适用）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | 边距测量类型（像素、百分比或毫米）。 |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | 数字证书的密码。 |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | 签名原因。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | 顺时针旋转角度。 |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | 文档的数字签名属性。对于 PDF 签名，可以使用 [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/) 实例设置高级属性。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Width 和 Height 属性的测量类型（像素、百分比或毫米）。 |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | 文档页上的拉伸模式。 |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | 文档页面上签名区域的顶部 Y 位置，使用测量单位（像素、百分比或毫米；参见 `MeasureType` `LocationMeasureType`）。 |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | 数字签名的透明度，范围为 0.0 到 1.0。默认值为 0。 |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | LTV（长期验证）验证标志。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | 图像在文档页上的垂直对齐方式。 |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | 签名的可见性。 |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | 文档页面上签名区域的宽度，以测量值（像素、百分比或毫米）表示。测量单位由 `MeasureType` 通过 SizeMeasureType 属性定义。 |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | XAdES 类型。默认值为 None（XAdES 已关闭）。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 签名将放置在所有文档页面上。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 额外的签名外观。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | 图像签名的边框设置。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 签名选项的文档类型（`DocumentType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 签名扩展。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | 签名图像的文件路径，仅在未指定 `image_stream` 时使用。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | 签名图像流。如果指定，则始终替代 ImageFilePath 使用。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 用于签名的文档页码。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 指定要签名的页面的选项。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | 放置图像于文档上的区域矩形。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | 形状位置定义了形状在文档布局中应呈现的位置。仅适用于 Word 文档。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 签名类型（`SignatureType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | 文本签名的 Z 顺序位置，用于确定重叠签名的显示顺序。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 将证书和外观图像传递给构造函数
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # 在页面上显示签名，位于此位置并具有此大小
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # 签名中存储的信息
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
使用 `DigitalSignOptions` 的任务指南：

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
