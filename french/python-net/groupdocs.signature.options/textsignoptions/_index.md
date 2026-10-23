---
title: "TextSignOptions classe"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de signature de texte."
type: docs
url: /fr/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Représente les options de signature de texte.

En savoir plus

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

Le type TextSignOptions expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Initialise une nouvelle instance de la classe TextSignOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Initialise une nouvelle instance de la classe TextSignOptions avec du texte. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Les paramètres d'arrière-plan de la signature. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Les paramètres de bordure. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | La police de la signature. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | La couleur de premier plan de la signature. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Le titre du champ de formulaire texte dans lequel placer la signature texte. Ne peut être utilisé que lorsque `signature_implementation` est défini sur `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Le type de champ de formulaire dans lequel placer la signature texte. Cette propriété n'est applicable que lorsque `signature_implementation` est définie sur `TextSignatureImplementation.FORM_FIELD` (c’est‑à‑dire TextToFormField). La valeur par défaut est `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | La hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres). L'unité est déterminée par la propriété `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | L'alignement horizontal de la signature sur la page du document. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | La position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres tels que définis par la propriété `MeasureType` LocationMeasureType). Fonctionne si l'alignement horizontal n'est pas spécifié. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés `left` et `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | L'espace entre la signature et les bords du document. S'applique uniquement lorsque l'alignement horizontal ou vertical est spécifié. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | L'attribut natif. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | L'angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | La position de la forme définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Le type de forme pour placer du texte. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | L'ID unique de la signature, utilisable dans les options de vérification et pris en charge uniquement pour les documents PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Le type d'implémentation de signature texte. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | Le mode d'étirement sur la page du document. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Le texte de la signature. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | L'alignement horizontal du texte à l'intérieur d'une signature, pris en charge uniquement pour les implémentations de signature Image et Annotation (voir la propriété `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | L'alignement vertical du texte à l'intérieur d'une signature. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | La position Y supérieure de la signature sur la page du document, exprimée en unités de mesure (pixels, pourcentage ou millimètres). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | La transparence de la signature, un nombre flottant compris entre 0.0 (opaque) et 1.0 (transparent). La valeur par défaut est 0.0 (opaque). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | L'alignement vertical de la signature sur la page du document. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | La largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres ; voir les propriétés `MeasureType` `SizeMeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La signature sera placée sur toutes les pages du document. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'apparence supplémentaire de la signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Le type de document des options de signature (`DocumentType`). (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Les extensions de signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | L'algorithme de hachage à utiliser pour les opérations cryptographiques. Pris en charge exclusivement pour les signatures numériques dans les fichiers PDF. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Le numéro de page du document pour la signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Les options pour spécifier les pages à signer. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Le type de signature (`SignatureType`). (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La position Z-order de la signature texte, qui détermine l'ordre d'affichage des signatures qui se chevauchent. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Guides de tâches qui utilisent `TextSignOptions` :

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
