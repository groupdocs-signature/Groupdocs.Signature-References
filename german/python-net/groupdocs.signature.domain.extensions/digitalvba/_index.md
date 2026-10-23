---
title: "DigitalVBA-Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die digitale Signatur für VBA-Projekte von Tabellenkalkulationen dar."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Stellt die digitale Signatur für VBA-Projekte von Tabellenkalkulationen dar.

Bietet die Möglichkeit, ein VBA-Projekt in Tabellenkalkulationsdokumentformaten wie `Xlsm` oder `Xltm` zu signieren. Wenn mehrere [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) Erweiterungen zu [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/) hinzugefügt werden, wird nur die erste während der Signierung verwendet.

Der DigitalVBA-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einer Zertifikatsdatei. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einem Zertifikat-Stream. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Erhält eine Kopie dieses Objekts. (geerbt von [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Der Dateipfad des digitalen Zertifikats, wird nur verwendet, wenn `CertificateStream` nicht angegeben ist. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Der digitale Zertifikat-Stream. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateFilePath verwendet. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | Die Signaturkommentare. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Das Passwort des digitalen Zertifikats. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | Die Einstellung, die bestimmt, ob nur das VBA‑Projekt signiert wird. Wenn True, wird das Tabellenkalkulationsdokument selbst nicht signiert; nur das VBA‑Projekt wird signiert. |

### Beispiel

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Makros im Tabellenblatt signieren
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Erweiterung hinzufügen, um das VBA‑Projekt digital zu signieren
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Überprüfen, ob der Signaturteil des VBA‑Projekts hinzugefügt wurde
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Siehe auch
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
