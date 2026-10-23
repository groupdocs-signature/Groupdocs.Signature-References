---
title: "Classe ImageSignOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de signature Image."
type: docs
url: /fr/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Représente les options de signature Image.

En savoir plus :
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Le type ImageSignOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Initialise une nouvelle instance de la classe ImageSignOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Initialise ImageSignOptions avec un fichier image. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Initialise une nouvelle instance ImageSignOptions avec un flux d'image. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Efface les ressources internes. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Crée une nouvelle instance ImageSignOptions avec une image prédéfinie à partir d'une chaîne Base64. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Les paramètres de bordure pour la signature d'image. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | La hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres ; voir `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | L'alignement horizontal de la signature sur la page du document. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Le chemin d'accès du fichier image de la signature, utilisé uniquement si `image_stream` n'est pas spécifié. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Le flux d'image de la signature. S'il est spécifié, il est toujours utilisé à la place de ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | La position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres). Fonctionne si l'alignement horizontal n'est pas spécifié. Voir `MeasureType` pour le type de mesure de localisation. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés gauche et haut. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | L'espace entre la signature et les bords du document. Fonctionne uniquement si l'alignement horizontal ou vertical est spécifié. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Le rectangle de la zone où placer l'image sur le document. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | L'angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | La position de la forme définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | Le mode d'étirement sur la page du document. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | La position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres) telle que définie par `MeasureType` LocationMeasureType. Fonctionne si l'alignement vertical n'est pas spécifié. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | La transparence de la signature, variant de 0,0 (opaque) à 1,0 (transparent), par défaut 0 (opaque). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | L'alignement vertical de la signature sur la page du document. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | La largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres `MeasureType` type de mesure de taille). |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Créer des options de signature d'image avec le fichier image
        options = ImageSignOptions("signature.jpg")
        # Définir la position et la taille de la signature
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Guides de tâches qui utilisent `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
