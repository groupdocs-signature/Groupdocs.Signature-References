---
title: "allow_not_yet_valid 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "允许使用尚未生效的证书进行签名的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

允许使用尚未生效的证书进行签名的标志。默认值为 False；使用此类证书签名会抛出 `GroupDocsSignatureException`，并且文档不会被签名。

验证器会将证书尚未生效前创建的签名报告为无效。此类证书通常是为以后日期签发的，或者计算机时钟不正确。当此标志为 True 时，文档仍会被签名，并向在 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) 中设置的日志记录器写入警告。

证书会与 UTC 当前时间进行比较。此标志适用于与 [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) 相同的证书，用于控制已过期的证书。

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### 另见
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
