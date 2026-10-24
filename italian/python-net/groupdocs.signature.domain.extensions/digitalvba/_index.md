---
title: "classe DigitalVBA"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta la firma digitale per progetti VBA di fogli di calcolo."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Rappresenta la firma digitale per progetti VBA di fogli di calcolo.

Fornisce la possibilità di firmare un progetto VBA nei formati di documento foglio di calcolo come `Xlsm` o `Xltm`. Se più estensioni [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) vengono aggiunte a [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), solo la prima viene utilizzata durante la firma.

Il tipo DigitalVBA espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Inizializza una nuova istanza della classe DigitalVBA con un file di certificato. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Inizializza una nuova istanza della classe DigitalVBA con un flusso di certificato. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Ottiene una copia di questo oggetto. (eredita da [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Il percorso del file del certificato digitale, usato solo se `CertificateStream` non è specificato. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Il flusso del certificato digitale. Se questa proprietà è specificata, viene sempre usata al posto di CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | I commenti della firma. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | La password del certificato digitale. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | L'impostazione che determina se firmare solo il progetto VBA. Quando True, il documento del foglio di calcolo stesso non viene firmato; solo il progetto VBA viene firmato. |

### Esempio

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Firma le macro all'interno del foglio di calcolo
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Aggiungi estensione per firmare digitalmente il progetto VBA
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Verifica che la parte della firma del progetto VBA sia stata aggiunta
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Vedi anche
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
