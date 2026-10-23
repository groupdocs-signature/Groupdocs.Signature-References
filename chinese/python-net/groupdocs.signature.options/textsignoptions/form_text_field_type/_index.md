---
title: "form_text_field_type 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "用于放置文本签名的表单字段类型。"
type: docs
url: /zh/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/
is_root: false
weight: 2060
---


## form_text_field_type property

要放置文本签名的表单字段类型。仅当 `signature_implementation` 设置为 `TextSignatureImplementation.FORM_FIELD`（即 TextToFormField）时此属性适用。默认值为 `FormTextFieldType.ALL_TEXT_TYPES`。

### Definition:
```python
@property
def form_text_field_type(self):
    ...
@form_text_field_type.setter
def form_text_field_type(self, value):
    ...
```

### 另见
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
