---
title: DigitalVBA class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents digital signature for Spreadsheets VBA projects."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Represents digital signature for Spreadsheets VBA projects.

Provides ability to sign a VBA project in spreadsheet document formats such as `Xlsm` or `Xltm`. If multiple [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) extensions are added to [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), only the first is used during signing.

The DigitalVBA type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Initializes a new instance of the DigitalVBA class with a certificate file. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Initializes a new instance of the DigitalVBA class with a certificate stream. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Gets a copy of this object. (inherited from [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Properties
| Property | Description |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | The digital certificate file path, used only if `CertificateStream` is not specified. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | The digital certificate stream. If this property is specified it is always used instead of CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | The signature comments. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | The password of the digital certificate. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | The setting that determines whether only the VBA project is signed. When True, the spreadsheet document itself is not signed; only the VBA project is signed. |

### Example

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Sign macros within the spreadsheet
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Add extension for signing VBA project digitally
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Verify that the VBA project signature part was added
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### See Also
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
