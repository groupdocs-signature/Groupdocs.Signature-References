---
title: "propriété whitelisted_resources"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "La liste des fragments d'adresses des ressources externes qui sont chargées même lorsque LoadOptions.SkipExternalResources est vrai."
type: docs
url: /fr/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

La liste des fragments d'adresses des ressources externes qui sont chargés même lorsque [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) est vrai. La valeur par défaut est une liste vide.

Une ressource est chargée lorsque son adresse complète contient l'un des fragments. La comparaison ignore la casse, et les fragments vides sont ignorés. Privilégiez les fragments longs tels que `\"https://cdn.example.com/images/\"` : un fragment court correspond également à d'autres adresses qui le contiennent par hasard.

Définir cette propriété sur `None` vide la liste. La liste n'a aucun effet lorsque [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) est false, car alors chaque ressource externe est chargée.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Voir aussi
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
