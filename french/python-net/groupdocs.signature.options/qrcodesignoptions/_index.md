---
title: "Classe QrCodeSignOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de signature QR-Code."
type: docs
url: /fr/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Représente les options de signature QR-Code.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

Le type QrCodeSignOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Initialise une nouvelle instance de la classe QRCodeSignOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Initialise une instance d'options de signature QR‑code avec le texte spécifié. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Initialise une nouvelle instance de la classe QrCodeSignOptions avec du texte. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | L'alignement du texte dans l'image QR‑code résultante, la valeur par défaut est None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | L'objet personnalisé à sérialiser dans le contenu QR‑Code. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | L'implémentation de chiffrement des données utilisée pour encoder et décoder le texte ou les données de signature du code QR. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | Le type de QR-Code. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | La couleur de premier plan des barres du QR code ; l'utilisation de cette propriété peut entraîner des problèmes de vérification, donc utilisez‑la avec précaution. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | La hauteur de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres ; voir `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | L'alignement horizontal du QR code sur une page de document. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | L'espace entre les éléments du QR code et les bordures de l'image résultante. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | La position X gauche de la zone de signature sur une page de document en unités de mesure (pixels, pourcentages ou millimètres). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés gauche et haut. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | Le nom de fichier de l'image du logo QR-code. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | Le flux d'image du logo QR-code. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | L'espace spécifié par défaut entre les bords de l'Image et du Document (fonctionne si un alignement horizontal ou vertical est spécifié). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Le type de mesure de la marge (pixels, pourcentages ou millimètres). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | Le drapeau pour récupérer le contenu image du QR-Code d'une signature placée sur une page de document. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | Le type de fichier du contenu image retourné de la signature QR‑Code lorsque la propriété `return_content` est activée. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | L'angle de rotation en degrés, dans le sens des aiguilles d'une montre. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | Le mode d'étirement sur la page du document. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | La position Y supérieure de la zone de signature sur une page de document en unités de mesure (pixels, pourcentages ou millimètres). L'unité est définie par la propriété `LocationMeasureType` de type `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | La transparence de la signature QR code. La valeur varie de 0,0 à 1,0, avec une valeur par défaut de 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | L'alignement vertical de l'image sur une page de document. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | La largeur de la zone de signature sur la page du document en valeurs de mesure (pixels, pourcentage ou millimètres tels que définis par `MeasureType`). |
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

        signature.sign("signed.pdf", options)
```

### Guides
Guides de tâche qui utilisent `QrCodeSignOptions` :

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
