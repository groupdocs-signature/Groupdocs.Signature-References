---
title: "classe DigitalVBA"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente la signature numérique pour les projets VBA de feuilles de calcul."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Représente la signature numérique pour les projets VBA de feuilles de calcul.

Permet de signer un projet VBA dans des formats de documents de feuille de calcul tels que `Xlsm` ou `Xltm`. Si plusieurs extensions [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) sont ajoutées à [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), seule la première est utilisée lors de la signature.

Le type DigitalVBA expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Initialise une nouvelle instance de la classe DigitalVBA avec un fichier de certificat. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Initialise une nouvelle instance de la classe DigitalVBA avec un flux de certificat. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Obtient une copie de cet objet. (hérité de [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Le chemin du fichier de certificat numérique, utilisé uniquement si `CertificateStream` n'est pas spécifié. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Le flux du certificat numérique. Si cette propriété est spécifiée, elle est toujours utilisée à la place de CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | Les commentaires de la signature. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Le mot de passe du certificat numérique. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | Le paramètre qui détermine si seul le projet VBA est signé. Lorsque True, le document feuille de calcul lui‑même n'est pas signé ; seul le projet VBA est signé. |

### Exemple

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Signer les macros dans la feuille de calcul
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Ajouter une extension pour signer numériquement le projet VBA
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Vérifier que la partie de signature du projet VBA a été ajoutée
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Voir aussi
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
