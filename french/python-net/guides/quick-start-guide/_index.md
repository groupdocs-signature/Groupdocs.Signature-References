---
title: "Guide de démarrage rapide"
linkTitle: "Quick Start Guide"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Configurez un environnement virtuel, installez groupdocs-signature-net et exécutez trois exemples minimalistes : signer un PDF avec une signature texte, le rechercher pour des signatures, et les vérifier."
type: docs
url: /fr/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Ce guide donne un aperçu rapide de la façon de configurer et de commencer à utiliser GroupDocs.Signature for Python via .NET. La bibliothèque ajoute, trouve, vérifie, met à jour et supprime les signatures électroniques dans les fichiers PDF, Word, Excel, PowerPoint, OpenDocument et image avec quelques lignes de code.

## Prerequisites

Pour continuer, assurez‑vous d’avoir :

1. Un environnement configuré comme décrit dans le sujet [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Sous Linux et macOS, cela inclut quelques paquets système.
2. Optionnellement, une [Temporary License](https://purchase.groupdocs.com/temporary-license/) pour tester toutes les fonctionnalités du produit. Sans licence, la bibliothèque fonctionne en mode d’évaluation : elle traite les documents jusqu’à deux pages et ajoute une ligne d’évaluation à chaque page signée. Voir [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Pour les meilleures pratiques, utilisez un environnement virtuel pour gérer les dépendances. En savoir plus dans le guide [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Créez un environnement virtuel :

{{< tabs \"create-venv\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Activez‑le :

{{< tabs \"activate-venv\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs \"install-package\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

Voir [Installation](/signature/python-net/guides/installation/) pour figer une version et installer sans accès à PyPI.

## Example 1: Sign a PDF with a Text Signature

Ouvrez un document, décrivez la signature avec [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), et enregistrez la copie signée.

{{< tabs \"sign_pdf_with_text_signature\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Ouvrez le document ; le with‑block libère le fichier lorsqu’il se termine
    with Signature("sample.pdf") as signature:
        # Une signature texte à 100 pixels du bord gauche et du bord supérieur de la première page
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signez et enregistrez le résultat dans un nouveau fichier ; la source reste inchangée
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_sample.pdf\" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Trouvez les signatures déjà présentes dans un document. `search` prend une liste d'options de recherche, une par type de signature à rechercher, et les renvoie dans `result.signatures`.

{{< tabs \"search_document_for_signatures\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Recherchez les signatures texte sur chaque page
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"search-document-signatures.txt\" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Vérifiez qu'un document possède la signature attendue. La vérification réussit lorsqu'une signature texte contenant exactement ce texte est trouvée.

{{< tabs \"verify_text_signature\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"verify-text-signature.txt\" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Enregistrez chaque exemple dans son propre fichier `.py` à côté des fichiers d'exemple. Votre dossier devrait ressembler à ceci :

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Exécutez un exemple depuis ce dossier :

{{< tabs \"run-the-app\">}}
{{< tab \"Windows\" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

Lorsque vous avez terminé, désactivez l'environnement virtuel en exécutant `deactivate` ou en fermant votre shell.

## Apply a License

Définissez la variable d'environnement `GROUPDOCS_LIC_PATH` sur le chemin complet de votre fichier de licence, et la licence est appliquée automatiquement lorsque `groupdocs.signature` est importé. Aucun code n'est nécessaire. Vous pouvez également l'appliquer dans le code une fois, avant tout autre appel :

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

Le sujet [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) couvre les deux méthodes ainsi que la licence à consommation.

## Next Steps

Après avoir maîtrisé les bases, explorez des ressources supplémentaires :
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
