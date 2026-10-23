---
title: "Signer le document avec une signature numérique"
linkTitle: "Digital Signature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Découvrez les avantages d'utiliser des signatures numériques pour signer des documents en toute sécurité. Apprenez comment ajouter des signatures numériques de manière programmatique en Python grâce à des instructions étape par étape."
type: docs
url: /fr/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

À l'ère numérique actuelle, garantir l'authenticité et l'intégrité des documents électroniques est crucial. Une méthode très efficace pour y parvenir est l'utilisation de signatures numériques. Dans ce guide, nous explorerons le monde des signatures numériques, en expliquant ce qu'elles sont, pourquoi elles sont essentielles, et comment vous pouvez exploiter GroupDocs.Signature for Python via .NET pour signer électroniquement vos documents de manière fluide.

## What is a Digital Signature?

Une signature numérique est un mécanisme cryptographique permettant de vérifier l'authenticité et l'intégrité des documents électroniques. Elle offre une forte garantie que le document provient d'un expéditeur connu et n'a pas été altéré par des sources non autorisées. Les signatures numériques sont généralement représentées par des certificats contenant des clés privées (pour la signature) et publiques (pour la vérification). Diverses normes de cryptographie à clé publique, telles que le format PFX, sont couramment utilisées à cette fin.
L'image ci-dessous montre à quoi ressemble une signature numérique sur une page de document PDF par défaut.

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

Les certificats expirés ou pas encore valides sont rejetés : `sign` lève [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) avec un message tel que "The signing certificate expired on …". Pour signer quand même avec un tel certificat, définissez `allow_expired` ou `allow_not_yet_valid` sur `True`.

### Follow these steps to sign your documents with a digital signature

1. Installez le package GroupDocs.Signature en utilisant pip :
```bash
pip install groupdocs-signature-net
```

2. Créez une nouvelle instance de la classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) et transmettez le chemin du document source en tant que paramètre du constructeur.
3. Instanciez l'objet [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) avec le certificat requis et son mot de passe.
4. Appelez la méthode [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) de l'instance de la classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) et transmettez‑lui le [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/).

L'exemple ci-dessous montre comment signer un document PDF avec une e‑signature numérique en utilisant Python. Nous pouvons signer tout autre format de document pris en charge de la même manière.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Créer des options de signature numérique avec le fichier de certificat
        options = DigitalSignOptions("certificate.pfx")

        # Définir le mot de passe du certificat
        options.password = "1234567890"

        # Optionnel : une image qui montre la signature sur la page
        options.image_file_path = "signature.jpg"

        # Définir la position de la signature
        options.left = 100
        options.top = 400

        # Signez le document et enregistrez le résultat
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` est le certificat d'exemple utilisé dans cet exemple (mot de passe `1234567890`). Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) pour le télécharger.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Vous pouvez personnaliser davantage la signature numérique avec des options supplémentaires : la taille de la signature sur la page, ainsi que le contact, le motif et le lieu enregistrés dans celle‑ci :

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Passez le certificat et l'image d'apparence au constructeur
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Afficher la signature sur la page, à cette position et taille
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Informations stockées dans la signature
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` est le certificat d'exemple utilisé dans cet exemple (mot de passe `1234567890`). Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) pour le télécharger.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Vous pouvez également charger le certificat depuis un flux. Gardez le flux ouvert jusqu'à ce que `sign` renvoie :

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Chargez le certificat depuis un flux
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Définir la position et la taille de la signature
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` est le certificat d'exemple utilisé dans cet exemple (mot de passe `1234567890`). Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Ce guide montre comment utiliser [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) pour signer des documents avec des signatures numériques. Il explique comment charger les documents, configurer des signatures basées sur un certificat et enregistrer les fichiers signés en toute sécurité. Les fonctionnalités avancées, telles que l'apparence de la signature et les informations stockées dans la signature, sont également couvertes. Consultez les ressources associées pour plus de détails sur les flux de travail de signature numérique.

## More Resources

### GitHub Examples

Vous pouvez facilement exécuter le code ci‑dessus et voir la fonctionnalité en action dans nos exemples GitHub :

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

En plus de la bibliothèque Python complète, nous proposons des applications en ligne simples mais puissantes et gratuites.

Pour signer des PDF, Word, Excel, PowerPoint et d'autres documents, vous pouvez utiliser les applications en ligne de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
