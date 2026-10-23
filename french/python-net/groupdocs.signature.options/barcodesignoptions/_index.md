---
title: "classe BarcodeSignOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de signature de code-barres."
type: docs
url: /fr/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Représente les options de signature de code-barres.

En savoir plus

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

Le type BarcodeSignOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | L'alignement du texte dans l'image du code-barres résultante. La valeur par défaut est None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | Le type de code-barres. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | La couleur de premier plan des barres du code-barres ; son utilisation peut entraîner des problèmes de vérification, donc utilisez‑la avec précaution. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | La hauteur de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres). Voir `MeasureType` pour le type de mesure de taille. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | L'alignement horizontal de l'image sur une page de document. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | L'espace entre les éléments du code-barres et les bordures de l'image résultante. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | La position X gauche de la zone de signature sur la page du document, exprimée en unités de mesure (pixels, pourcentages ou millimètres). Voir `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés gauche et haut. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | L'espace spécifié par défaut entre l'image et les bords du document (s'applique lorsque l'alignement horizontal ou vertical est défini). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | Le type de mesure de la marge (pixels, pourcentages ou millimètres). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | Le drapeau indiquant s'il faut récupérer le contenu de l'image du code-barres d'une signature placée sur une page de document. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | Le type de fichier du contenu d'image retourné de la signature Barcode lorsque la propriété `return_content` est activée. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | L'angle de rotation dans le sens des aiguilles d'une montre. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | Le mode d'étirement sur la page du document. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | La position Y supérieure de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres). Voir `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | La transparence de la signature du code-barres, variant de 0,0 ( totalement opaque) à 1,0 ( totalement transparente) ; la valeur par défaut est 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | L'alignement vertical de l'image du code-barres sur une page de document. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | La largeur de la zone de signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres) telle que définie par `MeasureType`. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La signature sera placée sur toutes les pages du document. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'apparence supplémentaire de la signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Les paramètres d'arrière-plan de la signature. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Les paramètres de bordure. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Le type de document des options de signature (`DocumentType`). (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Les extensions de signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | La police de la signature. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Le titre du champ de formulaire texte dans lequel placer la signature texte. Ne peut être utilisé que lorsque `signature_implementation` est défini sur `TextSignatureImplementation.FORM_FIELD`. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Le type de champ de formulaire dans lequel placer la signature texte. Cette propriété ne s'applique que lorsque `signature_implementation` est défini sur `TextSignatureImplementation.FORM_FIELD` (c.-à-d. TextToFormField). La valeur par défaut est `FormTextFieldType.ALL_TEXT_TYPES`. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | L'algorithme de hachage à utiliser pour les opérations cryptographiques. Pris en charge exclusivement pour les signatures numériques dans les fichiers PDF. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | L'attribut natif. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Le numéro de page du document pour la signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Les options pour spécifier les pages à signer. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | La position de la forme définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Le type de forme pour placer du texte. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | L'ID unique de la signature, utilisable dans les options de vérification et pris en charge uniquement pour les documents PDF. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Le type d'implémentation de signature texte. (hérité de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Le type de signature (`SignatureType`). (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Le texte de la signature. (hérité de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | L'alignement horizontal du texte à l'intérieur d'une signature, pris en charge uniquement pour les implémentations de signature Image et Annotation (voir la propriété `TextSignatureImplementation` SignatureImplementation). (hérité de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | L'alignement vertical du texte à l'intérieur d'une signature. (hérité de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La position Z-order de la signature texte, qui détermine l'ordre d'affichage des signatures qui se chevauchent. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Guides de tâches qui utilisent `BarcodeSignOptions` :

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
