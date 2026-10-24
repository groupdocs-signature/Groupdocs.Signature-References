---
title: "DigitalVBA-klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Geeft een digitale handtekening voor Spreadsheets VBA-projecten weer."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Geeft een digitale handtekening voor Spreadsheets VBA-projecten weer.

Biedt de mogelijkheid om een VBA‑project te ondertekenen in spreadsheet‑documentformaten zoals `Xlsm` of `Xltm`. Als meerdere [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)‑extensies worden toegevoegd aan [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), wordt alleen de eerste gebruikt tijdens het ondertekenen.

Het DigitalVBA-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatbestand. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatstroom. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Haalt een kopie van dit object op. (geërfd van [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Het pad naar het digitale certificaatbestand, alleen gebruikt als `CertificateStream` niet is opgegeven. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | De digitale certificaatstroom. Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | De handtekeningcommentaren. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Het wachtwoord van het digitale certificaat. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | De instelling die bepaalt of alleen het VBA-project wordt ondertekend. Wanneer True, wordt het spreadsheet‑document zelf niet ondertekend; alleen het VBA-project wordt ondertekend. |

### Voorbeeld

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Macro's ondertekenen binnen het spreadsheet.
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Voeg extensie toe voor het digitaal ondertekenen van het VBA-project
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Verifieer dat het handtekeningonderdeel van het VBA-project is toegevoegd
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Zie ook
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
