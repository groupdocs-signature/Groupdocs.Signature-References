---
title: "Classe SwissAddress"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente l'adresse du créancier ou du débiteur."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Représente l'adresse du créancier ou du débiteur.

Vous pouvez soit définir la rue, le numéro de maison, le code postal et la ville (type d’adresse structurée), soit la ligne d’adresse 1 et 2 (type d’éléments d’adresse combinés).

Le type SwissAddress expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | La ligne d’adresse 1, contenant le nom de la rue, le numéro de maison ou la boîte postale, est facultative et n’est utilisée que pour les adresses à éléments combinés. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | La ligne d’adresse 2, qui contient le code postal et la ville, est obligatoire pour les adresses à éléments combinés. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | Le code pays ISO à deux lettres. Le code pays est obligatoire sauf si l’ensemble de l’adresse contient des valeurs nulles ou vides. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | Le numéro de maison. Ce champ n’est utilisé que pour les adresses structurées et est facultatif. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | Le nom, soit le prénom et le nom de famille d’une personne physique, soit le nom de l’entreprise d’une personne morale. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | Le code postal. Ce champ n’est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | La rue de l’adresse, sans numéro de maison ; facultative et utilisée uniquement pour les adresses structurées. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | La ville ou la cité, utilisée uniquement pour les adresses structurées et obligatoire pour ce type. |

### Voir aussi
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
