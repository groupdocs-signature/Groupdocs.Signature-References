---
title: "Classe Mailmark2D"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Encode et décode le texte intégré dans le Mailmark 2D de Royal Mail."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Encode et décode le texte intégré dans le Mailmark 2D de Royal Mail.

Le type Mailmark2D expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Initialise les données combinées Royal Mail Mailmark avec les valeurs par défaut des données primaires et secondaires. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Renvoie une copie de cet objet. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | La classe de l'élément. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | L'espace optionnel à l'usage du client. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | Le mode d'encodage du code-barres DataMatrix. Valeur par défaut : `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | La propriété contient le code postal de l'adresse de livraison avec DPS, qui pour les adresses intérieures se compose d'une zone (1‑2 caractères), d'un district (1‑2 caractères), d'un secteur (1 caractère), d'une unité (2 caractères) et du DPS (2 caractères), doit respecter un format PAF® valide et a une longueur maximale de 9 caractères. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | L'identifiant de la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | L'identifiant unique de l'article au sein de l'ID de la chaîne d'approvisionnement, requis sur chaque code-barres Mailmark pour une identification unique pendant au moins 90 jours (valeur maximale : 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | Le code postal de retour à l'expéditeur sans DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | Le drapeau qui indique le niveau de service de retour à l'expéditeur demandé. La longueur maximale est de 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | Le groupe unique de clients impliqués dans l'envoi. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | L'ID pays UPU (longueur maximale : 4 caractères). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | L'identifiant de version du code-barres pertinent pour chaque ID de type d'information. |

### Voir aussi
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
