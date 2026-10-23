---
title: "issuer_name 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "要验证的证书的颁发者名称。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/
is_root: false
weight: 2060
---


## issuer_name property

要验证的证书的颁发者名称。

该值区分大小写。如果设置了此属性，验证将检查签名的发行者名称是否包含或等于传入的值。

### Definition:
```python
@property
def issuer_name(self):
    ...
@issuer_name.setter
def issuer_name(self, value):
    ...
```

### 另见
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
