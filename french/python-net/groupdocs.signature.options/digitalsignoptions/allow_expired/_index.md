---
title: "propriété allow_expired"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le drapeau qui permet de signer avec un certificat dont la période de validité est terminée."
type: docs
url: /fr/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Le drapeau qui permet de signer avec un certificat dont la période de validité a expiré. La valeur par défaut est False ; signer avec un certificat expiré lève `GroupDocsSignatureException` et le document n'est pas signé.

Les validateurs signalent qu'une signature réalisée avec un certificat expiré n'est pas valide. Réglez cette propriété sur True uniquement lorsque vous avez besoin de cette signature, par exemple pour tester avec un ancien certificat. Le document est alors signé et un avertissement est écrit dans le journal configuré dans [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Le certificat est comparé à l'heure actuelle en UTC, et non à [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). Le drapeau s'applique au certificat fourni par [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) ou [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), et, lorsqu'une feuille de calcul est signée, au certificat de la première extension [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/). Les signatures numériques d'images n'utilisent pas de certificat et ne sont pas vérifiées. Un certificat dont la période de validité n'a pas encore commencé est contrôlé par [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Voir aussi
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
