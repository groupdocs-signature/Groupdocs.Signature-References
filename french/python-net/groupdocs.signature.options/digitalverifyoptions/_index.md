---
title: "Classe DigitalVerifyOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Conserve les options pour vérifier la signature numérique d'un document."
type: docs
url: /fr/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Conserve les options pour vérifier la signature numérique d'un document.

En savoir plus

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Le type DigitalVerifyOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Initialise une instance DigitalVerifyOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Initialise une instance DigitalVerifyOptions avec le chemin de fichier du certificat numérique fourni. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Initialise une instance DigitalVerifyOptions avec le flux du certificat fourni. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Le certificat X509Certificate2 obtenu à partir du chemin de fichier ou du flux du certificat. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Le chemin de fichier du certificat numérique. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Le flux du certificat numérique. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Les commentaires de la signature numérique à valider. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Le contact de la signature à valider. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Le nom de l'émetteur du certificat à valider. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | L'emplacement de la signature à valider. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Le mot de passe du certificat numérique si requis. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | La raison de la signature numérique à valider. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Le début de la plage de date et d'heure de la signature numérique à valider. Une valeur None sera ignorée. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | La fin de la plage de date et d'heure de la signature numérique à valider. Une valeur null sera ignorée. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Le nom distinctif du sujet du certificat à valider ; la vérification vérifie si le nom du sujet de la signature contient ou est égal à cette valeur sensible à la casse. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Le drapeau indiquant si chaque page du document doit être vérifiée. Par défaut, la valeur est True. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Les extensions supplémentaires pour la vérification des options de signature alternatives. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Le drapeau de propriété valide. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Le numéro de page du document à vérifier ; s'il n'est pas défini, toutes les pages du document sont vérifiées pour la première occurrence (la valeur minimale est 1). (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Les options de page pour spécifier les pages à vérifier. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La position de la forme dans la mise en page du document utilisée pour vérifier les signatures dans les en-têtes/pieds de page. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
