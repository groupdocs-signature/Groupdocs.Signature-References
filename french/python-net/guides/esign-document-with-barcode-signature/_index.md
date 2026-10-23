---
title: "Signer électroniquement un document avec une signature Barcode"
linkTitle: "Barcode Signature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Cet article explique comment ajouter une signature Barcode sur la page d'un document avec diverses options telles que le type de code-barres, le texte du code-barres, le positionnement, l'alignement et d'autres paramètres visuels avec GroupDocs.Signature pour Python via .NET."
type: docs
url: /fr/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

Un **barcode** ou **bar code** est une façon de présenter des données sous une forme visuelle, lisible par machine. En général, le barcode est une image de forme rectangulaire composée de lignes noires parallèles et d'espaces blancs de différentes largeurs.
Les barcodes sont utilisés dans divers domaines où une identification rapide est nécessaire – comme partie du processus d'achat dans les magasins de détail, dans les entrepôts pour suivre les stocks, et sur les factures pour faciliter la comptabilité, parmi de nombreuses autres utilisations.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Les barcodes permettent de stocker des données liées aux produits telles que les dates de fabrication et de péremption, le nom du fabricant, le pays d'origine et le prix du produit. De nos jours, il existe de nombreux types de barcodes car différentes entreprises utilisent différentes combinaisons de chiffres et de barres dans leurs barcodes selon leurs besoins. Du point de vue de la signature de documents, le Barcode peut contenir différents caractères (lettres, chiffres ou symboles) et peut avoir diverses longueurs et tailles en fonction du type et des paramètres pour conserver les informations de signature, le titre, le sujet ou de courtes données chiffrées.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Pour spécifier différentes options pour la signature Barcode, GroupDocs.Signature pour Python via .NET propose la classe [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). Les principaux champs sont :

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Voici les étapes pour signer électroniquement un document avec la signature Barcode en utilisant l'API GroupDocs.Signature pour Python via .NET :
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Cet exemple montre comment signer un document PDF avec une signature Barcode en utilisant Python :

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Créer des options de signature barcode avec le texte à encoder
        options = BarcodeSignOptions("John Smith")

        # Définir le type de barcode
        options.encode_type = BarcodeTypes.CODE128

        # Définir la position et la taille du barcode
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Signez le document et enregistrez le résultat
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Vous pouvez personnaliser davantage la signature barcode avec des options supplémentaires : alignement et marges, couleur de la barre, position du texte encodé, marges internes, arrière-plan, bordure et transparence :

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Transmettre le texte et le type de barcode au constructeur
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Placer le barcode dans le coin inférieur droit de la page
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Couleur de la barre, texte encodé sous les barres, espace à l'intérieur de la bordure
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Arrière-plan, bordure et transparence
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature prend en charge différents types de barcode. Chaque type accepte son propre jeu de caractères et de longueurs, choisissez donc le texte correspondant au type. Cet exemple signe un document avec quatre barcodes de types différents en un seul appel :

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # Un objet d'options de signature par barcode, placé l'un sous l'autre
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_barcode_types.pdf\" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Ce guide montre comment utiliser [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) pour ajouter des signatures basées sur des codes-barres aux documents. Il couvre la création, la configuration et l'application des signatures de codes-barres avec la prise en charge de différents types de codes-barres et des options de personnalisation. Pour aller plus loin, consultez les guides associés sur les informations de document et les techniques de signature avancées.

## More Resources

### GitHub Examples

Vous pouvez facilement exécuter le code ci‑dessus et voir la fonctionnalité en action dans nos exemples GitHub :

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

En plus de la bibliothèque Python complète, nous proposons des applications en ligne simples mais puissantes et gratuites.

Pour générer des codes-barres et/ou signer vos fichiers avec des codes-barres gratuitement, vous pouvez utiliser l'application en ligne [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

Pour signer des PDF, Word, Excel, PowerPoint et d'autres documents, vous pouvez utiliser les autres applications en ligne de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
