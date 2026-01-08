---
title: verify method
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 90
---

## verify {#groupdocs.signature.options.VerifyOptions}

Verifies the document signatures with given VerifyOptions data.


### Returns 


Returns instance of [`VerificationResult`](/signature/python-net/groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.


```python
def verify(self, verify_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| verify_options | groupdocs.signature.options.VerifyOptions | The signature verification options. |


## verify {#System.Collections.Generic.List`1[[GroupDocs.Signature.Options.VerifyOptions]]}





```python
def verify(self, verify_options_list):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| verify_options_list | System.Collections.Generic.List`1[[GroupDocs.Signature.Options.VerifyOptions]] |  |



### See Also
* module [`groupdocs.signature`](../../)
* class [`Signature`](/signature/python-net/groupdocs.signature/signature)
* class [`VerificationResult`](/signature/python-net/groupdocs.signature.domain/verificationresult)
