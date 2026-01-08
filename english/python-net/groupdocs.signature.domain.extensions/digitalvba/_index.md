---
title: DigitalVBA class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 40
---

## DigitalVBA class

Represents digital signature for Spreadsheets VBA projects.
It provides ability to sign VBA project at specific Spreadsheets document formats like Xlsm or Xltm.
If several DigitalVBA extensions are added to DigitalSignOptions.Extensions only first is involved in document signing.



**Inheritance:** [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba) → 
[`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension)



The DigitalVBA type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#System.String-System.String) | Initializes a new instance of the DigitalVBA class with certificate file. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#io.RawIOBase-System.String) | Initializes a new instance of the DigitalVBA class with certificate stream. |


### Properties
| Property | Description |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments) | Gets or sets the signature comments. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password) | Gets or sets the password of digital certificate. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project) | Gets or sets setting of only VBA project signing.<br/>If set to true, the SpreadSheet document will not be signed, but the VBA project will be signed. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path) | Gets digital certificate file path.<br/>This property is used only if CertificateStream is not specified. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream) | Gets digital certificate stream.<br/>If this property is specified it is always used instead CertificateFilePath. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/clone/#) | Gets a copy of this object. |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba)
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension)
