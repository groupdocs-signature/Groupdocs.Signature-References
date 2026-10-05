---
title: form_text_field_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The type of form field to place the text signature into."
type: docs
url: /python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/
is_root: false
weight: 2060
---


## form_text_field_type property

The type of form field to place the text signature into. This property is applicable only when `signature_implementation` is set to `TextSignatureImplementation.FORM_FIELD` (i.e., TextToFormField). The default value is `FormTextFieldType.ALL_TEXT_TYPES`.

### Definition:
```python
@property
def form_text_field_type(self):
    ...
@form_text_field_type.setter
def form_text_field_type(self, value):
    ...
```

### See Also
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
