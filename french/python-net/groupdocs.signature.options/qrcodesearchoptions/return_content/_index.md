---
title: "propriété return_content"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "L'indicateur qui détermine si le contenu image du QR‑Code est renvoyé pour chaque signature sur une page de document."
type: docs
url: /fr/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/
is_root: false
weight: 2040
---


## return_content property

Le drapeau qui détermine si le contenu image du QR‑Code est renvoyé pour chaque signature sur une page de document. Lorsqu'il est défini sur True, les données d'image brutes sont conservées dans la propriété `content` de la signature en utilisant le format spécifié par `return_content_type`. Désactivé par défaut.

### Definition:
```python
@property
def return_content(self):
    ...
@return_content.setter
def return_content(self, value):
    ...
```

### Voir aussi
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
