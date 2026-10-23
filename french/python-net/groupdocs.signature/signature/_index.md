---
title: "Classe Signature"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente la classe principale qui contrôle le processus de signature de documents."
type: docs
url: /fr/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Représente la classe principale qui contrôle le processus de signature de documents.

En savoir plus sur les fonctionnalités de GroupDocs.Signature :
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Le type Signature expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Initialise une nouvelle instance de Signature avec un document fourni sous forme de flux. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un flux de document et des options de chargement. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un document fourni par un flux et des [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) optionnels. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un flux de document, des options de chargement et les paramètres de signature. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un document fourni par chemin de fichier. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Initialise une nouvelle instance de Signature avec le document fourni par chemin de fichier et des options de chargement. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec le document fourni par un chemin de fichier et des [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) optionnels. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un document fourni par chemin de fichier, des options de chargement et les paramètres de signature. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Supprime le [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) spécifié du document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Supprime la liste fournie de signatures du document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Supprime les signatures du type spécifié du document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Supprime les signatures de la liste `SignatureType` spécifiée du document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Supprime une signature par son Id de signature spécifique du document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Supprime les signatures spécifiées du document. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Nettoie les ressources internes utilisées par l'objet signature. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Génère un aperçu des pages du document. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Génère un aperçu de signature basé sur les SignOptions fournis. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Obtient des informations sur les pages du document : leurs tailles, la hauteur maximale d'une page, la largeur d'une page avec la hauteur maximale. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Recherche des signatures dans un document en utilisant une liste de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Recherche des signatures dans le document en utilisant les options de recherche fournies et filtre les résultats selon le prédicat spécifié. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Recherche les types de signature spécifiés dans le document par la valeur `SignatureType`. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Recherche des signatures dans le document en utilisant toutes les options de recherche disponibles et filtre les résultats selon le prédicat spécifié. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Signe le document avec [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Signe un document avec [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Signe le document avec SignOptions et enregistre le résultat à l'emplacement de fichier spécifié. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Signe le document avec [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat à l'emplacement de fichier spécifié en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat à l'emplacement de fichier spécifié. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat à l'emplacement de fichier spécifié en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis. |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Met à jour la BaseSignature de signature passée dans le document. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Met à jour les signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) transmises dans le document. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Vérifie les signatures du document avec les données VerifyOptions fournies. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Vérifie les signatures du document en utilisant les options de vérification fournies et filtre les résultats selon le prédicat spécifié. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Vérifie les signatures du document avec une liste de données VerifyOptions. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Vérifie les signatures de documents en utilisant les options de vérification fournies et filtre les résultats avec le prédicat donné. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Guides de tâches qui utilisent `Signature` :

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Voir aussi
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
