---
title: "Classe CertificateVerifyOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Conserve les options pour vérifier les documents de certificat."
type: docs
url: /fr/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Conserve les options pour vérifier les documents de certificat.

En savoir plus

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

Le type CertificateVerifyOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Initialise une nouvelle instance de TextVerifyOptions avec les valeurs par défaut. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Initialise une nouvelle instance de CertificateVerifyOptions avec le sujet à vérifier. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | La propriété indique si le certificat est expiré en fonction du résultat de la validation. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | L'émetteur du certificat à vérifier. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Le type de correspondance de texte utilisé pour la vérification. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Le processus de vérification doit fournir une validation de chaîne X.509 en utilisant la politique de validation de base. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Le numéro de série du certificat à vérifier. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Le sujet du certificat à vérifier. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | L'empreinte du certificat à vérifier. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Le drapeau indiquant si chaque page du document doit être vérifiée. Par défaut, la valeur est True. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Les extensions supplémentaires pour la vérification des options de signature alternatives. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Le drapeau de propriété valide. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Le numéro de page du document à vérifier ; s'il n'est pas défini, toutes les pages du document sont vérifiées pour la première occurrence (la valeur minimale est 1). (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Les options de page pour spécifier les pages à vérifier. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La position de la forme dans la mise en page du document utilisée pour vérifier les signatures dans les en-têtes/pieds de page. (hérité de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
