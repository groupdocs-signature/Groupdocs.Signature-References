---
title: "Classe SignatureSettings"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les paramètres de personnalisation du comportement de Signature."
type: docs
url: /fr/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Représente les paramètres pour personnaliser le comportement de [`Signature`](/signature/python-net/groupdocs.signature/signature/).

Le type SignatureSettings expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Initialise une instance par défaut de SignatureSettings avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Initialise une instance par défaut de SignatureSettings avec l'implémentation du Logger. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | La culture par défaut utilisée lors du traitement des documents. La valeur par défaut est "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | L'indicateur indiquant si les signatures de métadonnées de document standard telles que Auteur, Propriétaire, date de création et date de modification sont incluses dans la liste des métadonnées. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Les indicateurs de niveau de journal qui déterminent quels types de messages sont transmis à [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | L'implémentation du journal utilisé pour la journalisation (Erreurs, Avertissements, Traces). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | L'indicateur qui détermine si le document source est réenregistré lorsque la méthode Delete n'a aucune signature affectée à supprimer. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | L'indicateur qui détermine si le document source est réenregistré lorsque la méthode `Update` n'a aucune signature à mettre à jour. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | L'indicateur qui détermine si les signatures supprimées sont incluses dans le résultat des informations du document. Chaque [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) possède un indicateur `Deleted` pour indiquer si elle a été supprimée. |

### Voir aussi
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
