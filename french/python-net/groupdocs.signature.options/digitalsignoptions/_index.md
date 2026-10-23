---
title: "Classe DigitalSignOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options de signature numérique."
type: docs
url: /fr/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Représente les options de signature numérique.

En savoir plus

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

Le type DigitalSignOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Initialise une nouvelle instance de la classe DigitalSignOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Initialise une nouvelle instance de DigitalSignOptions avec un fichier de certificat. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Initialise une nouvelle instance de DigitalSignOptions avec un flux de certificat. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Initialise une nouvelle instance de la classe DigitalSignOptions avec un fichier de certificat et un fichier d'image d'apparence. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Initialise une nouvelle instance de DigitalSignOptions avec un fichier de certificat et un flux d'image d'apparence. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Initialise une nouvelle instance de DigitalSignOptions avec un flux de certificat et un fichier d'image d'apparence. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Initialise une nouvelle instance de DigitalSignOptions avec un flux de certificat et un flux d'image d'apparence. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Efface les ressources internes. (hérité de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Crée une nouvelle instance de ImageSignOptions avec une image prédéfinie à partir d'une chaîne Base64. (hérité de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Le drapeau qui permet de signer avec un certificat dont la période de validité a expiré. La valeur par défaut est False ; signer avec un certificat expiré lève `GroupDocsSignatureException` et le document n'est pas signé. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Le drapeau qui permet de signer avec un certificat dont la période de validité n'a pas encore commencé. La valeur par défaut est False ; signer avec un tel certificat lève `GroupDocsSignatureException` et le document n'est pas signé. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Le chemin du fichier du certificat numérique. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Le flux du certificat numérique. Si cette propriété est spécifiée, elle est toujours utilisée à la place de CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Le contact de la signature. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | La fonction de hachage personnalisée utilisée pour signer le document, permettant aux utilisateurs d'implémenter leur propre logique de signature numérique. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | La hauteur de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres ; voir `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | L'alignement horizontal de l'image sur une page de document. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | La position X gauche de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres tels que définis par `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | L'emplacement de la signature. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés left et top. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | L'espace spécifié par défaut entre l'image et les bords du document (s'applique lorsque l'alignement horizontal ou vertical est spécifié). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Le type de mesure de la marge (pixels, pourcentages ou millimètres). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Le mot de passe du certificat numérique. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | La raison de la signature. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | L'angle de rotation dans le sens des aiguilles d'une montre. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Les propriétés de la signature numérique pour le document. Pour la signature PDF, des propriétés avancées peuvent être définies en utilisant une instance de [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Le type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | Le mode d'étirement sur la page du document. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | La position Y supérieure de la zone de signature sur la page du document en unités de mesure (pixels, pourcentages ou millimètres ; voir `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | La transparence de la signature numérique, allant de 0.0 à 1.0. La valeur par défaut est 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | Le drapeau de validation LTV (Long Term Validation). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | L'alignement vertical de l'image sur une page de document. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | La visibilité de la signature. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | La largeur de la zone de signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres). L'unité de mesure est définie par `MeasureType` via la propriété SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | Le type XAdES. La valeur par défaut est None (XAdES désactivé). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La signature sera placée sur toutes les pages du document. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'apparence supplémentaire de la signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Les paramètres de bordure pour la signature d'image. (hérité de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Le type de document des options de signature (`DocumentType`). (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Les extensions de signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | L'algorithme de hachage à utiliser pour les opérations cryptographiques. Pris en charge exclusivement pour les signatures numériques dans les fichiers PDF. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Le chemin du fichier de l'image de signature, utilisé uniquement si `image_stream` n'est pas spécifié. (hérité de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Le flux d'image de signature. S'il est spécifié, il est toujours utilisé à la place de ImageFilePath. (hérité de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Le numéro de page du document pour la signature. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Les options pour spécifier les pages à signer. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Le rectangle de la zone où placer l'image sur le document. (hérité de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | La position de la forme définit où la forme doit être présentée dans la mise en page du document. Disponible uniquement pour les documents Word. (hérité de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Le type de signature (`SignatureType`). (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La position Z-order de la signature texte, qui détermine l'ordre d'affichage des signatures qui se chevauchent. (hérité de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Exemple

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

### Guides
Guides de tâches qui utilisent `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
