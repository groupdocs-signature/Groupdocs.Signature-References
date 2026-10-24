---
title: "DigitalVBA-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar digital signatur för kalkylblads‑VBA‑projekt."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Representerar digital signatur för kalkylblads‑VBA‑projekt.

Tillhandahåller möjlighet att signera ett VBA-projekt i kalkylbladsdokumentformat som `Xlsm` eller `Xltm`. Om flera [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)‑tillägg läggs till i [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), används endast det första vid signering.

DigitalVBA-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Initierar en ny instans av DigitalVBA-klassen med en certifikatfil. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Initierar en ny instans av DigitalVBA-klassen med en certifikatström. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Hämtar en kopia av detta objekt. (ärvd från [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Den digitala certifikatfilens sökväg, används endast om `CertificateStream` inte är angivet. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Den digitala certifikatströmmen. Om denna egenskap är angiven används den alltid istället för CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | Signaturkommentarerna. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Lösenordet för det digitala certifikatet. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | Inställningen som bestämmer om endast VBA-projektet ska signeras. När True signeras inte själva kalkylbladsdokumentet; endast VBA-projektet signeras. |

### Exempel

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Signera makron i kalkylbladet
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Lägg till tillägg för att digitalt signera VBA-projekt
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Verifiera att VBA-projektets signaturdel har lagts till
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Se även
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
