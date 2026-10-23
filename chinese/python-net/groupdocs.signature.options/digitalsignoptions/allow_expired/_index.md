---
title: "allow_expired 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "允许使用已过期证书进行签名的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

允许使用已过期证书进行签名的标志。默认值为 False；使用已过期的证书签名会抛出 `GroupDocsSignatureException`，并且文档不会被签名。

验证器会将使用已过期证书创建的签名报告为无效。仅在确实需要此类签名时（例如使用旧证书进行测试）才将此属性设为 True。文档随后被签名，并向在 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) 中设置的记录器写入警告。

证书会与 UTC 当前时间进行比较，而不是与 [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) 比较。此标志适用于由 [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/)、[`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) 或 [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/) 提供的证书；当对电子表格进行签名时，还适用于第一个 [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) 扩展的证书。图像的数字签名不使用证书，也不进行检查。尚未生效的证书受 [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) 控制。

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### 另见
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
