---
title: "skip_external_resources 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "阻止文档加载外部资源的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

阻止文档加载外部资源的标志。默认值为 True；除匹配 [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) 的资源外，外部资源均不加载。

文档可以引用存储在外部的资源，例如链接的图像、通过 INCLUDEPICTURE 字段插入的图片、演示文稿和电子表格中的链接图片，以及 SVG 图像引用的图像和样式表。加载此类资源会使库请求其地址。在处理不受信任文档的服务器上，文档可能利用此功能让服务器向内部地址发送请求（服务器端请求伪造），而 UNC 或 `file://` 路径可能导致 Windows 将账户的 NTLM 凭据发送到其他主机。在离线或空气隔离的安装环境中，请求会失败或等待超时。

被跳过的资源不会在页面预览或保存为图像的文档中绘制，图像、条形码和二维码搜索也无法检测到它们。仅对受信任的文档将此属性设为 False，并且最好使用 [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) 来允许特定地址。

此设置适用于文字处理文档、演示文稿、电子表格和 SVG 图像，包括归档中的文档。对于 SVG 图像，读取前会移除不允许的引用，且不符合良好 XML 结构的 SVG 图像会被拒绝。此设置不控制证书吊销检查、时间戳服务器或许可。

此属性取代了 [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/)，其含义相反。

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### 另见
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
