---
title: "Document eSign avec signature texte"
linkTitle: "Text Signature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Cet article explique comment signer un document avec une signature texte en utilisant l’API GroupDocs.Signature for Python via .NET. Apprenez comment ajouter une signature numérique à un PDF de façon programmatique en Python."
type: docs
url: /fr/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Une signature électronique **Text** est un texte arbitraire ajouté à un document de manière native selon le type de document. GroupDocs.Signature fournit la fonctionnalité de signature texte et permet de personnaliser un large éventail de paramètres de texte — du nom, taille et couleur de la police à l’alignement, bordures, effets d’ombre, etc. Voici à quoi peut ressembler une signature texte :

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Essayons d’ajouter une signature texte à un PDF de façon programmatique en utilisant Python.

Pour manipuler les signatures texte de façon programmatique, [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) fournit la classe [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) et l’ensemble du flux de travail est aussi simple que ceci :

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Cet exemple montre comment ajouter une signature texte à un document en utilisant Python :

{{< tabs \"sign_with_text_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Créer les options de signature texte
        options = TextSignOptions("John Smith")

        # Définir la position et la taille de la signature
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Définir la couleur du texte et la police
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Signez le document et enregistrez le résultat
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"signed_text.pdf\" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Vous pouvez personnaliser davantage la signature texte avec des options supplémentaires : alignement et marges, style de police, arrière‑plan, bordure, rotation et transparence. Lorsqu’un alignement est défini, il remplace la coordonnée `left` ou `top`, et la `margin` décale la signature du bord de la page.

{{< tabs \"sign_with_text_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # Placez la signature dans le coin inférieur droit de la page
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Style de police et couleur du texte
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Arrière‑plan, bordure, rotation et transparence
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # Rendre le texte sous forme d’image, ce qui dessine également la bordure sur les pages PDF
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Ce guide explique comment ajouter des signatures basées sur du texte aux documents avec [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Il couvre la configuration des propriétés du texte telles que la police, la couleur, la taille et la position, ainsi que l'application de la signature texte à un document. Le document signé est ensuite enregistré avec la signature texte ajoutée.

## More Resources

### GitHub Examples

Vous pouvez facilement exécuter le code ci‑dessus et voir la fonctionnalité en action dans nos exemples GitHub :

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

En plus de la bibliothèque Python complète, nous proposons des applications en ligne simples mais puissantes et gratuites.

Pour signer des PDF, Word, Excel, PowerPoint et d'autres documents, vous pouvez utiliser les applications en ligne de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
