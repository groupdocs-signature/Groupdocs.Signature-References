---
title: "propriété skip_external_resources"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le drapeau qui empêche le document de charger des ressources externes."
type: docs
url: /fr/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

L'indicateur qui empêche le document de charger des ressources externes. La valeur par défaut est True ; les ressources externes ne sont pas chargées sauf celles qui correspondent à [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Un document peut faire référence à des ressources stockées à l'extérieur, telles que des images liées, des images insérées par un champ INCLUDEPICTURE, des images liées dans des présentations et des feuilles de calcul, ainsi que des images et des feuilles de style référencées par une image SVG. Le chargement d’une telle ressource oblige la bibliothèque à demander son adresse. Sur un serveur qui traite des documents non fiables, un document pourrait utiliser cela pour faire envoyer des requêtes du serveur vers des adresses internes (falsification de requête côté serveur), et un chemin UNC ou `file://` pourrait amener Windows à envoyer les informations d’identification NTLM du compte à un autre hôte. Sur une installation hors ligne ou isolée, les requêtes échouent ou attendent un délai d’expiration.

Les ressources qui sont ignorées ne sont pas affichées dans les aperçus de page ni dans les documents enregistrés sous forme d'images, et la recherche d'images, de codes-barres et de QR‑code ne les voit pas. Réglez cette propriété sur False uniquement pour les documents de confiance, et privilégiez l'autorisation d'adresses spécifiques avec [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Ce paramètre s'applique aux documents de traitement de texte, aux présentations, aux feuilles de calcul et aux images SVG, y compris les documents contenus dans des archives. Pour les images SVG, les références non autorisées sont supprimées de l'image avant sa lecture, et une image SVG qui n'est pas du XML bien formé est rejetée. Le paramètre ne contrôle pas les vérifications de révocation de certificat, les serveurs d'horodatage ou la licence.

Cette propriété remplace [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), qui a le sens opposé.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Voir aussi
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
