---
title: "Signer un document avec une signature QR Code"
linkTitle: "QR Code Signature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Cet article explique comment signer des documents avec une signature électronique sous forme de QR code sur une page de document à l’aide de GroupDocs.Signature pour Python via l’API .NET."
type: docs
url: /fr/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

Le QR code (ou Quick Response code) est une forme de [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) bidimensionnel qui consiste en des carrés noirs disposés sur une grille carrée sur fond blanc. Les QR codes peuvent être lus par les caméras de smartphones ou des appareils spécialisés dédiés à la lecture de QR – scanners portables, terminaux mobiles, scanners de bureau, scanners intégrés, etc. En général, les QR codes contiennent des données pointant vers un site web ou une application, des e‑mails, des numéros de téléphone, des identifiants de produit ou des traceurs. Ainsi, le champ d’application des QR codes s’étend du marketing général et de l’identification d’articles à la gestion de documents.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Code Aztec | code DataMatrix | GS1 DataMatrix | GS1 code QR | QR |
| --- | --- | --- | --- | --- | --- |
| **Application** | * transport et billetterie;<br> * dans l'industrie aérienne pour les cartes d'embarquement électroniques;<br> * dans le ferroviaire pour les billets vendus en ligne et imprimés par les clients ou affichés sur les écrans de téléphones mobiles. Le code est scanné par un lecteur portable par le personnel à bord ou aux tourniquets pour valider le billet.<br> * médecine - bracelets d'identification des patients et étiquettes pour les médicaments à usage unique, etc. | * médias imprimés tels que les étiquettes et les lettres;<br> * objectifs d'ingénierie industrielle - marquage des composants, etc.;<br>  * industrie alimentaire - pour éviter que les produits alimentaires soient emballés et datés incorrectement; | Utilisé dans<br> * les soins de santé;<br> * le gouvernement;<br> * l'industrie.<br> Encode des informations supplémentaires sur l'article, telles que :<br> * le poids;<br> * la date d'expiration;<br> * le numéro de lot;<br> * la date de fabrication;<br> * etc. | Utilisé en marketing pour encoder des informations supplémentaires sur l'article sur l'emballage | Largement utilisé dans l'industrie automobile et les applications mobiles. Utile pour encoder une grande quantité de caractères de données et des URL spécifiques. |
| **Longueur** | 3067 alphanumériques,<br> 3832 numériques,<br> 1914 octets | 2335 alphanumériques,<br> 3116 numériques | 2335 alphanumériques,<br> 3116 numériques,<br> 1556 octets | 7089 alphanumériques,<br> 4296 numériques,<br> 2953 octets | 4296 alphanumériques,<br> 7089 numériques,<br> 2953 octets |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Lors de l'ajout d'une signature électronique de code QR à un document, les principaux paramètres sont le texte à encoder et le [type de code QR](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) qui doit être spécifié via la classe [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

Voici les étapes pour signer électroniquement un document avec la signature de code QR :

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

L'extrait de code ci-dessous montre comment signer un document PDF avec la signature de code QR en utilisant Python :

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Créer des options de signature de code QR avec le texte à encoder
        options = QrCodeSignOptions("John Smith")

        # Définir le type de code QR
        options.encode_type = QrCodeTypes.QR

        # Définir la position et la taille du code QR
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Signez le document et enregistrez le résultat
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Les autres types de QR code du tableau ci‑dessus sont définis de la même façon, par exemple `QrCodeTypes.AZTEC` ou `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Voici un exemple montrant comment créer une signature QR code plus complexe avec des personnalisations supplémentaires : alignement et marges, couleur du module, arrière‑plan et bordure :

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Passez le texte et le type de QR code au constructeur
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Placez le QR code dans le coin inférieur droit de la page
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Couleur du module, arrière‑plan et bordure pointillée avec un peu d'espace à l'intérieur
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Ce guide montre comment ajouter des signatures QR code aux documents en utilisant [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Il comprend les étapes pour générer une signature QR code, configurer ses propriétés comme la taille et l’encodage, et l’appliquer à un document. Les signatures QR code peuvent être utilisées pour une vérification rapide du document signé.

## More Resources

### GitHub Examples

Vous pouvez facilement exécuter le code ci‑dessus et voir la fonctionnalité en action dans nos exemples GitHub :

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

En plus de la bibliothèque Python complète, nous proposons des applications en ligne simples mais puissantes et gratuites.

Pour générer des QR codes et/ou signer vos fichiers avec des QR codes gratuitement, vous pouvez utiliser l’application en ligne [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

Pour signer des PDF, Word, Excel, PowerPoint et d'autres documents, vous pouvez utiliser les autres applications en ligne de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
