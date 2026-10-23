---
title: "PdfDigitalSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 PDF 数字签名属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

表示 PDF 数字签名属性。

PdfDigitalSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | 在没有证书的情况下初始化 PDF 数字签名。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | 使用指定的 X509 存储初始化 PDF 数字签名。将使用该存储中的第一张证书。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | 使用指定的 X509 存储和证书索引初始化 PDF 数字签名。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | 使用指定的 X509 证书初始化 PDF 数字签名。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | 克隆 PDF 数字签名实例。 |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | 比较签名属性以确定相等性。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | 重写 GetHashCode 方法。 |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | 从所有系统 X509 证书存储加载数字签名。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | 签名人提供的联系信息，以便收件人验证签名，例如电话号码。 |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | 签名的 CPU 主机名或物理位置。 |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | 签名的原因，例如（I agreeРІР‚В¦）。 |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | 标志强制显示或隐藏签名属性；当为 true 时，签名字段使用预定义的外观格式（例如，`Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`），默认值为 True。 |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | PDF 数字签名的时间戳。默认值为 None。 |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | PDF 数字签名的类型。 |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | 与数字签名关联的 X509 证书。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | 证书的自定义存储名称。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | 证书的存储位置。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | 证书的存储名称。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | 签名目的注释。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 签名创建日期。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | 指示此签名是否已从文档中删除的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 签名的高度。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | 指示此组件是表示签名 (`True`) 还是文档内容 (`False`) 的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | 数字签名有效且文档未被篡改。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 签名的左侧位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 签名的修改日期。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 找到签名的页码。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | 文档签署的时间。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 签名的唯一标识符，用于通过更新或删除操作修改文档中的签名。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 签名的类型。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | 证书的指纹。（继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 签名的顶部位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 签名的宽度。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | XAdES 类型（[`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)）。 （继承自 [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)） |

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
