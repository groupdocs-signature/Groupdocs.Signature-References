---
title: "propriété allow_not_yet_valid"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le drapeau qui permet de signer avec un certificat dont la période de validité n'a pas encore commencé."
type: docs
url: /fr/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Le drapeau qui permet de signer avec un certificat dont la période de validité n'a pas encore commencé. La valeur par défaut est False ; signer avec un tel certificat lève `GroupDocsSignatureException` et le document n'est pas signé.

Les validateurs signalent qu'une signature réalisée avant que le certificat ne devienne valide n'est pas valide. Un tel certificat est généralement émis pour une date ultérieure, ou l'horloge de l'ordinateur est incorrecte. Lorsque ce drapeau est True, le document est signé et un avertissement est écrit dans le journal configuré dans [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Le certificat est comparé à l'heure actuelle en UTC. Le drapeau s'applique aux mêmes certificats que [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), qui contrôle les certificats dont la période de validité est terminée.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Voir aussi
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
