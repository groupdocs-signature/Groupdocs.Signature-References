---
title: "FormFieldSignOptions classe"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de signature FormField pour les documents PDF."
type: docs
url: /fr/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

Représente les options de signature FormField pour les documents PDF.

Fournit des options pour créer ou mettre à jour les signatures de champs de formulaire dans les fichiers PDF.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

Le type FormFieldSignOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | Initialise une nouvelle instance de la classe PdfFormFieldSignOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | Initialise une nouvelle instance de la classe PdfFormFieldSignOptions avec une signature FormField. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | La hauteur de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres ; voir `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | L'alignement horizontal de l'image sur une page de document. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | La position X gauche de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | L'espace par défaut entre l'image et les bords du document (s'applique lorsque l'alignement horizontal ou vertical est défini). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | Le type de mesure de la marge (pixels, pourcentages ou millimètres). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | L'angle de rotation, mesuré dans le sens des aiguilles d'une montre. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | Le FormField de la signature. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | Le mode d'étirement sur la page du document. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | La position Y supérieure de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres). Voir `MeasureType` pour le type de mesure de localisation. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | La transparence de la signature du champ de formulaire. La valeur varie de 0,0 à 1,0, avec une valeur par défaut de 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | L'alignement vertical de l'image sur une page de document. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | La largeur de la zone de signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres ; voir `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La signature sera placée sur toutes les pages du document. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'apparence supplémentaire de la signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Les paramètres d'arrière-plan de la signature. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Les paramètres de bordure. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Le type de document des options de signature (`DocumentType`). (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Les extensions de signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | La police de la signature. (hérités de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | La couleur de premier plan de la signature. (héritée de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
